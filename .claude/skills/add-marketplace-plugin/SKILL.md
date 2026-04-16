---
name: add-marketplace-plugin
description: Add a Claude Code plugin to the marketplace from a GitHub URL. Use this skill whenever the user provides a GitHub repository URL and asks to add it as a plugin to the claude-code-marketplace. This includes phrases like "add this plugin", "add this repo to marketplace", "register this plugin", or any request containing a github.com URL for a plugin to be added. The skill extracts plugin metadata, updates marketplace.json, updates README.md, commits, and pushes.
---

# Add Marketplace Plugin

This skill adds a Claude Code plugin to the marketplace from a GitHub repository URL.

## Workflow

### Step 1: Parse the GitHub URL

From the user's input, extract the GitHub repository in format `owner/repo`.

Examples:
- `https://github.com/KenKaiii/minimal-claude` → `KenKaiii/minimal-claude`
- `github.com/KenKaiii/minimal-claude` → `KenKaiii/minimal-claude`
- `KenKaiii/minimal-claude` → `KenKaiii/minimal-claude`

### Step 2: Fetch Plugin Metadata

Use `WebFetch` to get information from the repository URL:
```
https://github.com/{owner}/{repo}
```

Extract:
- **name**: Derive from repo name (e.g., `minimal-claude` → `minimal-claude`)
- **description**: From the repo's description
- **author**: The GitHub owner/organization name
- **topics/keywords**: From repo topics if available
- **license**: If visible on the repo page

### Step 3: Determine Category

Pick the most appropriate category from these options:
- `development` - Developer tools, IDE plugins, code-related
- `productivity` - Tools that improve workflow efficiency
- `security` - Security-focused tools
- `communication` - Communication/messaging tools

Default to `development` unless the plugin clearly fits elsewhere.

### Step 4: Update marketplace.json

Read `.claude-plugin/marketplace.json`, then add a new plugin entry before the closing `]` of the plugins array.

Plugin entry format:
```json
{
  "name": "{plugin-name}",
  "source": {
    "source": "github",
    "repo": "{owner}/{repo}"
  },
  "description": "{description}",
  "category": "{category}",
  "repository": "https://github.com/{owner}/{repo}",
  "keywords": [{extracted keywords}],
  "author": {
    "name": "{author}"
  },
  "license": "{MIT or as-found}"
}
```

Use `Edit` to insert before the closing `]` of plugins array. Preserve valid JSON.

### Step 5: Update README.md

Read `README.md`, then add a new plugin section in alphabetical order within its category. Use this format:

```markdown
### {Plugin Name}

- **Name**: `{plugin-name}`
- **Description**: {description}
- **Category**: {category}
- **Author**: {author}
- **Repository**: <a href="https://github.com/{owner}/{repo}" target="_blank">{owner}/{repo}</a>
- **Keywords**: {keywords}
- **License**: {license}
- **Installation**:
  ```bash
  /plugin install {plugin-name}@claude-code-awesome
  ```
```

Insert in alphabetical order within the category section. Place before `## 🔧 Usage`.

### Step 6: Commit and Push

1. Run `git status` to see changes
2. Run `git add .claude-plugin/marketplace.json README.md`
3. Run `git commit -m "Add {plugin-name} plugin to marketplace"` with Co-Author footer
4. Run `git push`

### Step 7: Confirm

Tell the user the plugin was added successfully and provide the installation command.

## File Paths

- Marketplace manifest: `.claude-plugin/marketplace.json`
- README: `README.md`
- Both files are in the current working directory (claude-code-marketplace repo)
