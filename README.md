# Claude Code Awesome Marketplace

A curated marketplace for Claude Code plugins and extensions, focusing on useful tools that enhance your development workflow.

## ⚙️ Add this marketplace to Claude Code environment

```bash
/plugin marketplace add https://github.com/adrianR84/claude-code-marketplace
```

### Verifying Installation

To verify that the marketplace has been added successfully:

```bash
/plugin marketplace list
```

You should see `claude-code-awesome` in the list of available marketplaces.

## 🚀 Available Plugins

### Telegram Notifications

- **Name**: `telegram-notifications`
- **Description**: Telegram notifications for Claude Code events
- **Category**: Development
- **Author**: AdrianR84
- **Repository**: <a href="https://github.com/adrianR84/claude-code-telegram-notifications" target="_blank">adrianR84/claude-code-telegram-notifications</a>
- **Keywords**: telegram, notifications, hooks
- **Installation**:
  ```bash
  /plugin install telegram-notifications@claude-code-awesome
  ```

### Toast Notifications

- **Name**: `toast-notifications`
- **Description**: Windows toast notifications for Claude Code events using native Windows APIs
- **Category**: Development
- **Repository**: <a href="https://github.com/TianqiZhang/claude-code-toast" target="_blank">TianqiZhang/claude-code-toast</a>
- **Keywords**: windows toast, notifications
- **Installation**:
  ```bash
  /plugin install toast-notifications@claude-code-awesome
  ```

### Browserless

- **Name**: `browserless`
- **Description**: Browser automation and web scraping capabilities for Claude Code
- **Category**: Development
- **Repository**: <a href="https://github.com/adrianR84/browserless-claude-plugin" target="_blank">adrianR84/browserless-claude-plugin</a>
- **Keywords**: browser automation, web scraping
- **Installation**:
  ```bash
  /plugin install browserless@claude-code-awesome
  ```

### Greeting

- **Name**: `greeting`
- **Description**: A customizable greeting plugin for Claude Code that demonstrates user-configurable settings
- **Category**: Development
- **Repository**: <a href="https://github.com/adrianR84/claude-code-greeting" target="_blank">adrianR84/claude-code-greeting</a>
- **Keywords**: greeting
- **Installation**:
  ```bash
  /plugin install greeting@claude-code-awesome
  ```

### Protective Hooks

- **Name**: `protective-hooks`
- **Description**: Security hooks for Claude Code
- **Category**: Security
- **Repository**: <a href="https://github.com/adrianR84/claude-code-protective-hooks" target="_blank">adrianR84/claude-code-protective-hooks</a>
- **Keywords**: security, hooks, protection, secrets, dangerous-commands
- **Installation**:
  ```bash
  /plugin install protective-hooks@claude-code-awesome
  ```

### Claude Cybersecurity

- **Name**: `claude-cybersecurity`
- **Description**: AI-powered cybersecurity code review skill for Claude Code. 8 specialist agents, OWASP 2025, CWE Top 25, MITRE ATT&CK, 11 languages, zero configuration.
- **Category**: Security
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/claude-cybersecurity" target="_blank">AgriciDaniel/claude-cybersecurity</a>
- **Keywords**: cybersecurity, owasp, code-review, devsecops, vulnerability-scanner, appsec
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install claude-cybersecurity@claude-code-awesome
  ```

### RSS Aggregator

- **Name**: `rss-aggregator`
- **Description**: RSS feed aggregation and article content extraction — fetch entries and read articles as Markdown
- **Category**: Productivity
- **Author**: adrianR84
- **Repository**: <a href="https://github.com/adrianR84/rss-aggregator" target="_blank">adrianR84/rss-aggregator</a>
- **Keywords**: rss, feed, aggregator, articles
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install rss-aggregator@claude-code-awesome
  ```

### My MCPs

- **Name**: `my-mcps`
- **Description**: Claude Code plugin providing MCP server integrations for different services
- **Category**: Development
- **Author**: adrianR84
- **Repository**: <a href="https://github.com/adrianR84/claude-code-mcps" target="_blank">adrianR84/claude-code-mcps</a>
- **Keywords**: mcp, composio, dbhub, plugin
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install my-mcps@claude-code-awesome
  ```

### Andrej Karpathy Skills

- **Name**: `andrej-karpathy-skills`
- **Description**: Behavioral guidelines to reduce common LLM coding mistakes, derived from Andrej Karpathy's observations on LLM coding pitfalls
- **Category**: Productivity
- **Author**: forrestchang
- **Repository**: <a href="https://github.com/forrestchang/andrej-karpathy-skills" target="_blank">forrestchang/andrej-karpathy-skills</a>
- **Keywords**: guidelines, best-practices, coding, karpathy
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install andrej-karpathy-skills@claude-code-awesome
  ```

### Claude Code Skills

- **Name**: `claude-code-skills`
- **Description**: A collection of skills for Claude Code
- **Category**: Productivity
- **Author**: AdrianR84
- **Repository**: <a href="https://github.com/adrianR84/claude-code-skills" target="_blank">adrianR84/claude-code-skills</a>
- **Keywords**: skills
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install claude-code-skills@claude-code-awesome
  ```

### Claude Mem

- **Name**: `claude-mem`
- **Description**: Persistent memory system for Claude Code - context compression across sessions
- **Category**: Productivity
- **Author**: Alex Newman
- **Repository**: <a href="https://github.com/thedotmack/claude-mem" target="_blank">thedotmack/claude-mem</a>
- **Keywords**: memory, persistence, context, session, compression
- **License**: AGPL-3.0
- **Installation**:
  ```bash
  /plugin install claude-mem@claude-code-awesome
  ```

### Memsearch

- **Name**: `memsearch`
- **Description**: Automatic semantic memory for Claude Code — remembers what you worked on across sessions
- **Category**: Productivity
- **Author**: Zilliz
- **Repository**: <a href="https://github.com/zilliztech/memsearch" target="_blank">zilliztech/memsearch</a>
- **Keywords**: memory, semantic-search, milvus, markdown
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install memsearch@claude-code-awesome
  ```

### Remember

- **Name**: `remember`
- **Description**: Continuous memory for Claude Code. Extracts, summarizes, and compresses conversations into tiered daily logs. Claude remembers what you did yesterday.
- **Category**: Productivity
- **Author**: Digital Process Tools
- **Repository**: <a href="https://github.com/Digital-Process-Tools/claude-remember" target="_blank">Digital-Process-Tools/claude-remember</a>
- **Keywords**: memory, context, persistence, session
- **License**: Community License
- **Installation**:
  ```bash
  /plugin install remember@claude-code-awesome
  ```

### Wiki Skills

- **Name**: `wiki-skills`
- **Description**: An LLM-maintained personal wiki skills project for Claude Code — implements Karpathy's LLM Wiki pattern with 5 skills: wiki-init, wiki-ingest, wiki-query, wiki-lint, wiki-update.
- **Category**: Productivity
- **Author**: Kenny Chou
- **Repository**: <a href="https://github.com/kfchou/wiki-skills" target="_blank">kfchou/wiki-skills</a>
- **Keywords**: wiki, knowledge, karpathy, skills, memory
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install wiki-skills@claude-code-awesome
  ```

### LLM Wiki Compiler

- **Name**: `llm-wiki-compiler`
- **Description**: Compiles markdown knowledge files into a topic-based wiki. Implements Karpathy's LLM Knowledge Base pattern.
- **Category**: Productivity
- **Author**: Sumant
- **Repository**: <a href="https://github.com/ussumant/llm-wiki-compiler" target="_blank">ussumant/llm-wiki-compiler</a>
- **Keywords**: wiki, knowledge, markdown, karpathy, knowledge-base
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install llm-wiki-compiler@claude-code-awesome
  ```

### Skill Bus

- **Name**: `skill-bus`
- **Description**: Connect context, conditions, and other skills to any skill — no modification required
- **Category**: Productivity
- **Author**: Joey Nguyen
- **Repository**: <a href="https://github.com/joeymnguyen/skill-bus" target="_blank">joeymnguyen/skill-bus</a>
- **Keywords**: skills, hooks, subscriptions, context
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install skill-bus@claude-code-awesome
  ```

### Minimal Claude

- **Name**: `minimal-claude`
- **Description**: Intelligent Claude Code plugin that auto-configures linting, typechecking, and parallel agent-based fixing.
- **Category**: Development
- **Author**: KenKaiii
- **Repository**: <a href="https://github.com/KenKaiii/minimal-claude" target="_blank">KenKaiii/minimal-claude</a>
- **Keywords**: linting, typechecking, fixing, commit, quality, automation
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install minimal-claude@claude-code-awesome
  ```

### TDD Guard

- **Name**: `tdd-guard`
- **Description**: Automated Test-Driven Development enforcement — blocks implementation without failing tests
- **Category**: Development
- **Author**: Nizar Selander
- **Repository**: <a href="https://github.com/nizos/tdd-guard" target="_blank">nizos/tdd-guard</a>
- **Keywords**: tdd, hooks, automation, code-quality, claude-code, agentic-coding
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install tdd-guard@claude-code-awesome
  ```

### Micro Skill Pipeline

- **Name**: `micro-skill-pipeline`
- **Description**: Stop writing 200-line skills that Claude skims. Convert any skill into a gated micro-pipeline with hard YES/NO quality checks.
- **Category**: Development
- **Author**: stevesolun
- **Repository**: <a href="https://github.com/stevesolun/micro-skills" target="_blank">stevesolun/micro-skills</a>
- **Keywords**: skills, developer-tools, code-quality, ai-agents, quality-gates, claude-code, claude-skills, micro-skills, skills-pipeline
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install micro-skill-pipeline@claude-code-awesome
  ```

### Banana Claude

- **Name**: `banana-claude`
- **Description**: AI image generation Creative Director powered by Google Gemini Nano Banana models. Claude interprets intent, selects domain expertise, constructs optimized prompts, and orchestrates Gemini for best results.
- **Category**: Productivity
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/banana-claude" target="_blank">AgriciDaniel/banana-claude</a>
- **Keywords**: image-generation, ai-art, gemini, creative-director
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install banana-claude@claude-code-awesome
  ```

### Claude SEO

- **Name**: `claude-seo`
- **Description**: Comprehensive SEO analysis skill for Claude Code. 20 core sub-skills covering technical SEO, E-E-A-T, schema markup, image optimization, GEO/AEO, backlinks, local SEO, maps intelligence, semantic topic clustering, SXO, SEO drift monitoring, e-commerce SEO, international SEO with cultural profiles, Google API integration, and PDF reporting.
- **Category**: Productivity
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/claude-seo" target="_blank">AgriciDaniel/claude-seo</a>
- **Keywords**: seo, marketing-automation, technical-seo, e-e-a-t, schema, backlinks
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install claude-seo@claude-code-awesome
  ```

### Claude Ads

- **Name**: `claude-ads`
- **Description**: Comprehensive paid advertising audit & optimization skill for Claude Code. 250+ checks across Google, Meta, YouTube, LinkedIn, TikTok, Microsoft & Apple Ads with weighted scoring, parallel agents, industry templates, and AI creative generation.
- **Category**: Productivity
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/claude-ads" target="_blank">AgriciDaniel/claude-ads</a>
- **Keywords**: advertising, marketing-automation, ai-marketing, google-ads, meta-ads
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install claude-ads@claude-code-awesome
  ```

### Claude Obsidian

- **Name**: `claude-obsidian`
- **Description**: Claude + Obsidian knowledge companion. Persistent, compounding wiki vault based on Karpathy's LLM Wiki pattern. /wiki /save /autoresearch
- **Category**: Productivity
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/claude-obsidian" target="_blank">AgriciDaniel/claude-obsidian</a>
- **Keywords**: obsidian, second-brain, knowledge-management, wiki
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install claude-obsidian@claude-code-awesome
  ```

### Claude Prompts

- **Name**: `claude-prompts`
- **Description**: AI prompt database and builder skill for Claude Code. 2,500+ curated prompts across 19 categories and 17 AI models.
- **Category**: Productivity
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/claude-prompts" target="_blank">AgriciDaniel/claude-prompts</a>
- **Keywords**: prompt-engineering, prompts, ai
- **License**: MIT
- **Installation**:
  ```bash
  /plugin install claude-prompts@claude-code-awesome
  ```

## 🔧 Usage

Once installed, plugins will be available in your Claude Code environment. Refer to individual plugin documentation for specific usage instructions.

## 📄 License

This marketplace configuration is licensed under the MIT License. Individual plugins may have their own licenses - please refer to their respective repositories.

## 🔗 Links

- [Claude Code Documentation](https://code.claude.com/docs)
- [Plugin Marketplace Documentation](https://code.claude.com/docs/en/plugin-marketplaces)
- [Plugin Reference](https://code.claude.com/docs/en/plugins-reference)
