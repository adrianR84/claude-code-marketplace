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

## 🔧 Usage

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

## 🔧 Usage

Once installed, plugins will be available in your Claude Code environment. Refer to individual plugin documentation for specific usage instructions.

## 📄 License

This marketplace configuration is licensed under the MIT License. Individual plugins may have their own licenses - please refer to their respective repositories.

## 🔗 Links

- [Claude Code Documentation](https://code.claude.com/docs)
- [Plugin Marketplace Documentation](https://code.claude.com/docs/en/plugin-marketplaces)
- [Plugin Reference](https://code.claude.com/docs/en/plugins-reference)
