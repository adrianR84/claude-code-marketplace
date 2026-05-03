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

| Plugin | Version | Author | Description |
|--------|---------|--------|-------------|
| [telegram-notifications](#telegram-notifications) | 1.0.2 | AdrianR84 | Telegram notifications for Claude Code events |
| [toast-notifications](#toast-notifications) | 1.0.0 | TianqiZhang | Windows toast notifications for Claude Code events |
| [browserless](#browserless) | 1.0.2 | adrianR84 | Browser automation and web scraping capabilities |
| [greeting](#greeting) | 1.0.2 | adrianR84 | A customizable greeting plugin |
| [protective-hooks](#protective-hooks) | 1.0.1 | adrianR84 | Security hooks for Claude Code |
| [claude-cybersecurity](#claude-cybersecurity) | 1.1.0 | AgriciDaniel | AI-powered cybersecurity code review skill |
| [rss-aggregator](#rss-aggregator) | 1.0.4 | adrianR84 | RSS feed aggregation and article extraction |
| [my-mcps](#my-mcps) | 1.0.2 | adrianR84 | MCP server integrations |
| [andrej-karpathy-skills](#andrej-karpathy-skills) | 1.0.0 | forrestchang | Behavioral guidelines to reduce LLM coding mistakes |
| [claude-code-skills](#claude-code-skills) | 1.0.2 | AdrianR84 | A collection of skills for Claude Code |
| [claude-mem](#claude-mem) | 12.4.8 | Alex Newman | Persistent memory system for Claude Code |
| [memsearch](#memsearch) | 0.4.1 | Zilliz | Automatic semantic memory for Claude Code |
| [remember](#remember) | 0.7.0 | Digital Process Tools | Continuous memory for Claude Code |
| [wiki-skills](#wiki-skills) | 1.0.0 | Kenny Chou | LLM-maintained personal wiki skills |
| [llm-wiki-compiler](#llm-wiki-compiler) | 2.0 | Sumant | Compiles markdown into topic-based wiki |
| [skill-bus](#skill-bus) | 0.7.0 | Joey Nguyen | Connect context, conditions, and skills |
| [minimal-claude](#minimal-claude) | 1.6.1 | KenKaiii | Auto-configures linting, typechecking, and fixing |
| [tdd-guard](#tdd-guard) | 1.4.1 | Nizar Selander | Test-Driven Development enforcement |
| [micro-skill-pipeline](#micro-skill-pipeline) | 1.0.0 | stevesolun | Gated micro-pipeline for quality checks |
| [banana-claude](#banana-claude) | 1.4.1 | AgriciDaniel | AI image generation Creative Director |
| [claude-seo](#claude-seo) | 1.9.6 | AgriciDaniel | Comprehensive SEO analysis skill |
| [claude-ads](#claude-ads) | 1.5.1 | AgriciDaniel | Paid advertising audit & optimization |
| [claude-obsidian](#claude-obsidian) | 1.6.0 | AgriciDaniel | Claude + Obsidian knowledge companion |
| [claude-prompts](#claude-prompts) | 1.0.0 | AgriciDaniel | AI prompt database and builder |
| [prompt-mini](#prompt-mini) | 0.1.0 | nidhinjs | Forges weak prompts into structured prompts |
| [obsidian](#obsidian) | 1.0.1 | Steph Ango | Claude Skills for Obsidian |
| [atlas](#atlas) | 0.2.0 | pacifio | Atlas design language skill |
| [beads](#beads) | 1.0.3 | Steve Yegge | Distributed graph issue tracker for AI agents |
| [agent-session-resume](#agent-session-resume) | 0.1.1 | hacktivist123 | Reconstruct and continue prior AI coding-agent sessions |
| [waza-health](#waza-health) | 3.16.0 | Tw93 | Audits Claude Code config stack |
| [waza-think](#waza-think) | 3.16.0 | Tw93 | Turns rough ideas into approved plans |
| [waza-check](#waza-check) | 3.15.0 | Tw93 | Reviews code diffs, auto-fixes safe issues |
| [waza-hunt](#waza-hunt) | 3.17.0 | Tw93 | Finds root cause of errors and crashes |
| [waza-design](#waza-design) | 3.18.0 | Tw93 | Produces distinctive production-grade UI |
| [waza-read](#waza-read) | 3.14.0 | Tw93 | Fetches URLs/PDFs as clean Markdown |
| [waza-write](#waza-write) | 3.18.0 | Tw93 | Strips AI writing patterns, sounds natural |
| [waza-learn](#waza-learn) | 3.15.0 | Tw93 | Six-phase research workflow |
| [design-extract](#design-extract) | 1.0.0 | Manavarya Singh | Extract design language from any website |
| [claude-flow](#claude-flow) | 2.5.0 | rUv | Enterprise AI agent orchestration |
| [all-permissions](#all-permissions) | 1.0.2 | adrianR84 | Auto-approves tool calls after security scanning |
| [agentops](#agentops) | 2.39.0 | boshu2 | The operational layer for coding agents |
| [last30days](#last30days) | 3.1.1 | Matt Van Horn | Research any topic across Reddit, X, YouTube, HN, and more |
| [understand-anything](#understand-anything) | 2.3.1 | Lum1104 | Interactive knowledge graphs for codebase understanding |
| [everything-claude-code](#everything-claude-code) | 2.0.0-rc.1 | Affaan Mustafa | Agent harness performance optimization system |

### Telegram Notifications

- **Name**: `telegram-notifications`
- **Description**: Telegram notifications for Claude Code events
- **Category**: Development
- **Author**: AdrianR84
- **Repository**: <a href="https://github.com/adrianR84/claude-code-telegram-notifications" target="_blank">adrianR84/claude-code-telegram-notifications</a>
- **Keywords**: telegram, notifications, hooks
- **License**: MIT
- **Version**: 1.0.1
- **Installation**:
  ```bash
  /plugin install telegram-notifications@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Toast Notifications

- **Name**: `toast-notifications`
- **Description**: Windows toast notifications for Claude Code events using native Windows APIs
- **Category**: Development
- **Repository**: <a href="https://github.com/TianqiZhang/claude-code-toast" target="_blank">TianqiZhang/claude-code-toast</a>
- **Keywords**: windows toast, notifications
- **License**: MIT
- **Version**: 1.0.0
- **Installation**:
  ```bash
  /plugin install toast-notifications@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Browserless

- **Name**: `browserless`
- **Description**: Browser automation and web scraping capabilities for Claude Code
- **Category**: Development
- **Repository**: <a href="https://github.com/adrianR84/browserless-claude-plugin" target="_blank">adrianR84/browserless-claude-plugin</a>
- **Keywords**: browser automation, web scraping
- **License**: MIT
- **Version**: 1.0.2
- **Installation**:
  ```bash
  /plugin install browserless@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Greeting

- **Name**: `greeting`
- **Description**: A customizable greeting plugin for Claude Code that demonstrates user-configurable settings
- **Category**: Development
- **Repository**: <a href="https://github.com/adrianR84/claude-code-greeting" target="_blank">adrianR84/claude-code-greeting</a>
- **Keywords**: greeting
- **License**: MIT
- **Version**: 1.0.2
- **Installation**:
  ```bash
  /plugin install greeting@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Protective Hooks

- **Name**: `protective-hooks`
- **Description**: Security hooks for Claude Code
- **Category**: Security
- **Repository**: <a href="https://github.com/adrianR84/claude-code-protective-hooks" target="_blank">adrianR84/claude-code-protective-hooks</a>
- **Keywords**: security, hooks, protection, secrets, dangerous-commands
- **License**: MIT
- **Version**: 1.0.1
- **Installation**:
  ```bash
  /plugin install protective-hooks@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Claude Cybersecurity

- **Name**: `claude-cybersecurity`
- **Description**: AI-powered cybersecurity code review skill for Claude Code. 8 specialist agents, OWASP 2025, CWE Top 25, MITRE ATT&CK, 11 languages, zero configuration.
- **Category**: Security
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/claude-cybersecurity" target="_blank">AgriciDaniel/claude-cybersecurity</a>
- **Keywords**: cybersecurity, owasp, code-review, devsecops, vulnerability-scanner, appsec
- **License**: MIT
- **Version**: 1.1.0
- **Installation**:
  ```bash
  /plugin install claude-cybersecurity@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### RSS Aggregator

- **Name**: `rss-aggregator`
- **Description**: RSS feed aggregation and article content extraction — fetch entries and read articles as Markdown
- **Category**: Productivity
- **Author**: adrianR84
- **Repository**: <a href="https://github.com/adrianR84/rss-aggregator" target="_blank">adrianR84/rss-aggregator</a>
- **Keywords**: rss, feed, aggregator, articles
- **License**: MIT
- **Version**: 1.0.4
- **Installation**:
  ```bash
  /plugin install rss-aggregator@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### My MCPs

- **Name**: `my-mcps`
- **Description**: Claude Code plugin providing MCP server integrations for different services
- **Category**: Development
- **Author**: adrianR84
- **Repository**: <a href="https://github.com/adrianR84/claude-code-mcps" target="_blank">adrianR84/claude-code-mcps</a>
- **Keywords**: mcp, composio, dbhub, plugin
- **License**: MIT
- **Version**: 1.0.2
- **Installation**:
  ```bash
  /plugin install my-mcps@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Andrej Karpathy Skills

- **Name**: `andrej-karpathy-skills`
- **Description**: Behavioral guidelines to reduce common LLM coding mistakes, derived from Andrej Karpathy's observations on LLM coding pitfalls
- **Category**: Productivity
- **Author**: forrestchang
- **Repository**: <a href="https://github.com/forrestchang/andrej-karpathy-skills" target="_blank">forrestchang/andrej-karpathy-skills</a>
- **Keywords**: guidelines, best-practices, coding, karpathy
- **License**: MIT
- **Version**: 1.0.0
- **Installation**:
  ```bash
  /plugin install andrej-karpathy-skills@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Claude Code Skills

- **Name**: `claude-code-skills`
- **Description**: A collection of skills for Claude Code
- **Category**: Productivity
- **Author**: AdrianR84
- **Repository**: <a href="https://github.com/adrianR84/claude-code-skills" target="_blank">adrianR84/claude-code-skills</a>
- **Keywords**: skills
- **License**: MIT
- **Version**: 1.0.2
- **Installation**:
  ```bash
  /plugin install claude-code-skills@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Claude Mem

- **Name**: `claude-mem`
- **Description**: Persistent memory system for Claude Code - context compression across sessions
- **Category**: Productivity
- **Author**: Alex Newman
- **Repository**: <a href="https://github.com/thedotmack/claude-mem" target="_blank">thedotmack/claude-mem</a>
- **Keywords**: memory, persistence, context, session, compression
- **License**: AGPL-3.0
- **Version**: 12.4.8
- **Installation**:
  ```bash
  /plugin install claude-mem@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Memsearch

- **Name**: `memsearch`
- **Description**: Automatic semantic memory for Claude Code — remembers what you worked on across sessions
- **Category**: Productivity
- **Author**: Zilliz
- **Repository**: <a href="https://github.com/zilliztech/memsearch" target="_blank">zilliztech/memsearch</a>
- **Keywords**: memory, semantic-search, milvus, markdown
- **License**: MIT
- **Version**: 0.4.1
- **Installation**:
  ```bash
  /plugin install memsearch@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Remember

- **Name**: `remember`
- **Description**: Continuous memory for Claude Code. Extracts, summarizes, and compresses conversations into tiered daily logs. Claude remembers what you did yesterday.
- **Category**: Productivity
- **Author**: Digital Process Tools
- **Repository**: <a href="https://github.com/Digital-Process-Tools/claude-remember" target="_blank">Digital-Process-Tools/claude-remember</a>
- **Keywords**: memory, context, persistence, session
- **License**: Community License
- **Version**: 0.7.0
- **Installation**:
  ```bash
  /plugin install remember@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Wiki Skills

- **Name**: `wiki-skills`
- **Description**: An LLM-maintained personal wiki skills project for Claude Code — implements Karpathy's LLM Wiki pattern with 5 skills: wiki-init, wiki-ingest, wiki-query, wiki-lint, wiki-update.
- **Category**: Productivity
- **Author**: Kenny Chou
- **Repository**: <a href="https://github.com/kfchou/wiki-skills" target="_blank">kfchou/wiki-skills</a>
- **Keywords**: wiki, knowledge, karpathy, skills, memory
- **License**: MIT
- **Version**: 1.0.0
- **Installation**:
  ```bash
  /plugin install wiki-skills@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### LLM Wiki Compiler

- **Name**: `llm-wiki-compiler`
- **Description**: Compiles markdown knowledge files into a topic-based wiki. Implements Karpathy's LLM Knowledge Base pattern.
- **Category**: Productivity
- **Author**: Sumant
- **Repository**: <a href="https://github.com/ussumant/llm-wiki-compiler" target="_blank">ussumant/llm-wiki-compiler</a>
- **Keywords**: wiki, knowledge, markdown, karpathy, knowledge-base
- **License**: MIT
- **Version**: 2.0
- **Installation**:
  ```bash
  /plugin install llm-wiki-compiler@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Skill Bus

- **Name**: `skill-bus`
- **Description**: Connect context, conditions, and other skills to any skill — no modification required
- **Category**: Productivity
- **Author**: Joey Nguyen
- **Repository**: <a href="https://github.com/joeymnguyen/skill-bus" target="_blank">joeymnguyen/skill-bus</a>
- **Keywords**: skills, hooks, subscriptions, context
- **License**: MIT
- **Version**: 0.7.0
- **Installation**:
  ```bash
  /plugin install skill-bus@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Minimal Claude

- **Name**: `minimal-claude`
- **Description**: Intelligent Claude Code plugin that auto-configures linting, typechecking, and parallel agent-based fixing.
- **Category**: Development
- **Author**: KenKaiii
- **Repository**: <a href="https://github.com/KenKaiii/minimal-claude" target="_blank">KenKaiii/minimal-claude</a>
- **Keywords**: linting, typechecking, fixing, commit, quality, automation
- **License**: MIT
- **Version**: 1.6.1
- **Installation**:
  ```bash
  /plugin install minimal-claude@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### TDD Guard

- **Name**: `tdd-guard`
- **Description**: Automated Test-Driven Development enforcement — blocks implementation without failing tests
- **Category**: Development
- **Author**: Nizar Selander
- **Repository**: <a href="https://github.com/nizos/tdd-guard" target="_blank">nizos/tdd-guard</a>
- **Keywords**: tdd, hooks, automation, code-quality, claude-code, agentic-coding
- **License**: MIT
- **Version**: 1.4.1
- **Installation**:
  ```bash
  /plugin install tdd-guard@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Micro Skill Pipeline

- **Name**: `micro-skill-pipeline`
- **Description**: Stop writing 200-line skills that Claude skims. Convert any skill into a gated micro-pipeline with hard YES/NO quality checks.
- **Category**: Development
- **Author**: stevesolun
- **Repository**: <a href="https://github.com/stevesolun/micro-skills" target="_blank">stevesolun/micro-skills</a>
- **Keywords**: skills, developer-tools, code-quality, ai-agents, quality-gates, claude-code, claude-skills, micro-skills, skills-pipeline
- **License**: MIT
- **Version**: 1.0.0
- **Installation**:
  ```bash
  /plugin install micro-skill-pipeline@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Banana Claude

- **Name**: `banana-claude`
- **Description**: AI image generation Creative Director powered by Google Gemini Nano Banana models. Claude interprets intent, selects domain expertise, constructs optimized prompts, and orchestrates Gemini for best results.
- **Category**: Productivity
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/banana-claude" target="_blank">AgriciDaniel/banana-claude</a>
- **Keywords**: image-generation, ai-art, gemini, creative-director
- **License**: MIT
- **Version**: 1.4.1
- **Installation**:
  ```bash
  /plugin install banana-claude@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Claude SEO

- **Name**: `claude-seo`
- **Description**: Comprehensive SEO analysis skill for Claude Code. 20 core sub-skills covering technical SEO, E-E-A-T, schema markup, image optimization, GEO/AEO, backlinks, local SEO, maps intelligence, semantic topic clustering, SXO, SEO drift monitoring, e-commerce SEO, international SEO with cultural profiles, Google API integration, and PDF reporting.
- **Category**: Productivity
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/claude-seo" target="_blank">AgriciDaniel/claude-seo</a>
- **Keywords**: seo, marketing-automation, technical-seo, e-e-a-t, schema, backlinks
- **License**: MIT
- **Version**: 1.9.6
- **Installation**:
  ```bash
  /plugin install claude-seo@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Claude Ads

- **Name**: `claude-ads`
- **Description**: Comprehensive paid advertising audit & optimization skill for Claude Code. 250+ checks across Google, Meta, YouTube, LinkedIn, TikTok, Microsoft & Apple Ads with weighted scoring, parallel agents, industry templates, and AI creative generation.
- **Category**: Productivity
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/claude-ads" target="_blank">AgriciDaniel/claude-ads</a>
- **Keywords**: advertising, marketing-automation, ai-marketing, google-ads, meta-ads
- **License**: MIT
- **Version**: 1.5.1
- **Installation**:
  ```bash
  /plugin install claude-ads@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Claude Obsidian

- **Name**: `claude-obsidian`
- **Description**: Claude + Obsidian knowledge companion. Persistent, compounding wiki vault based on Karpathy's LLM Wiki pattern. /wiki /save /autoresearch
- **Category**: Productivity
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/claude-obsidian" target="_blank">AgriciDaniel/claude-obsidian</a>
- **Keywords**: obsidian, second-brain, knowledge-management, wiki
- **License**: MIT
- **Version**: 1.6.0
- **Installation**:
  ```bash
  /plugin install claude-obsidian@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Claude Prompts

- **Name**: `claude-prompts`
- **Description**: AI prompt database and builder skill for Claude Code. 2,500+ curated prompts across 19 categories and 17 AI models.
- **Category**: Productivity
- **Author**: AgriciDaniel
- **Repository**: <a href="https://github.com/AgriciDaniel/claude-prompts" target="_blank">AgriciDaniel/claude-prompts</a>
- **Keywords**: prompt-engineering, prompts, ai
- **License**: MIT
- **Version**: 1.0.0
- **Installation**:
  ```bash
  /plugin install claude-prompts@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Prompt Mini

- **Name**: `prompt-mini`
- **Description**: Forges weak Claude Code prompts into structured, credit-saving, framework-aware prompts.
- **Category**: Productivity
- **Author**: nidhinjs
- **Repository**: <a href="https://github.com/nidhinjs/prompt-mini" target="_blank">nidhinjs/prompt-mini</a>
- **Keywords**: prompts, claude-code, hooks, developer-tools
- **License**: MIT
- **Version**: 0.1.0
- **Installation**:
  ```bash
  /plugin install prompt-mini@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Obsidian

- **Name**: `obsidian`
- **Description**: Claude Skills for Obsidian — enables agents to work with Markdown, Bases, JSON Canvas, and the CLI.
- **Category**: Productivity
- **Author**: Steph Ango
- **Repository**: <a href="https://github.com/kepano/obsidian-skills" target="_blank">kepano/obsidian-skills</a>
- **Keywords**: cli, skills, obsidian, codex, claude
- **License**: MIT
- **Version**: 1.0.1
- **Installation**:
  ```bash
  /plugin install obsidian@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Atlas

- **Name**: `atlas`
- **Description**: Atlas design language skill. 180+ tokens, 50+ .atlas-* component classes, ~8 markdown reference docs. Teaches coding agents the Atlas aesthetic, vocabulary, and composition recipes — they generate code in your target stack.
- **Category**: Design
- **Author**: pacifio
- **Repository**: <a href="https://github.com/pacifio/ui" target="_blank">pacifio/ui</a>
- **Keywords**: design-system, ui, css, tokens, components, dark-theme, amoled, agent-ui, ai, shadcn, tailwind
- **License**: MIT
- **Version**: 0.2.0
- **Installation**:
  ```bash
  /plugin install atlas@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Beads

- **Name**: `beads`
- **Description**: AI-supervised issue tracker for coding workflows. Distributed graph issue tracker for AI agents, powered by Dolt.
- **Category**: Development
- **Author**: Steve Yegge
- **Repository**: <a href="https://github.com/gastownhall/beads" target="_blank">gastownhall/beads</a>
- **Keywords**: coding, agents, claude-code
- **License**: MIT
- **Version**: 1.0.3
- **Installation**:
  ```bash
  /plugin install beads@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Agent Session Resume

- **Name**: `agent-session-resume`
- **Description**: Adds the agent-session-resume skill for reconstructing and continuing prior AI coding-agent sessions.
- **Category**: Productivity
- **Author**: hacktivist123
- **Repository**: <a href="https://github.com/hacktivist123/agent-session-resume" target="_blank">hacktivist123/agent-session-resume</a>
- **Keywords**: agent-skills, handoff, session-resume, claude-code, coding-agents
- **License**: MIT
- **Version**: 0.1.1
- **Installation**:
  ```bash
  /plugin install agent-session-resume@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Waza Health

- **Name**: `waza-health`
- **Description**: Audits the full six-layer Claude Code config stack when Claude ignores instructions, behaves inconsistently, hooks malfunction, or MCP servers need auditing. Flags issues by severity.
- **Category**: Development
- **Author**: Tw93
- **Repository**: <a href="https://github.com/tw93/Waza" target="_blank">tw93/Waza</a>
- **Keywords**: config, auditing, hooks, mcp, debugging
- **License**: MIT
- **Version**: 3.16.0
- **Installation**:
  ```bash
  /plugin install waza-health@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Waza Think

- **Name**: `waza-think`
- **Description**: Turns rough ideas into approved plans with validated structure before writing code. Covers new features, architecture decisions, and value judgments about whether to build, keep, or remove something.
- **Category**: Development
- **Author**: Tw93
- **Repository**: <a href="https://github.com/tw93/Waza" target="_blank">tw93/Waza</a>
- **Keywords**: planning, architecture, decision-making, skills
- **License**: MIT
- **Version**: 3.16.0
- **Installation**:
  ```bash
  /plugin install waza-think@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Waza Check

- **Name**: `waza-check`
- **Description**: Reviews code diffs after implementation, auto-fixes safe issues, and runs specialist security and architecture reviewers on large diffs. Also triages issues and PRs.
- **Category**: Development
- **Author**: Tw93
- **Repository**: <a href="https://github.com/tw93/Waza" target="_blank">tw93/Waza</a>
- **Keywords**: code-review, security, architecture, auto-fix
- **License**: MIT
- **Version**: 3.15.0
- **Installation**:
  ```bash
  /plugin install waza-check@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Waza Hunt

- **Name**: `waza-hunt`
- **Description**: Finds root cause of errors, crashes, unexpected behavior, and failing tests before applying any fix.
- **Category**: Development
- **Author**: Tw93
- **Repository**: <a href="https://github.com/tw93/Waza" target="_blank">tw93/Waza</a>
- **Keywords**: debugging, error-fixing, troubleshooting, testing
- **License**: MIT
- **Version**: 3.17.0
- **Installation**:
  ```bash
  /plugin install waza-hunt@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Waza Design

- **Name**: `waza-design`
- **Description**: Produces distinctive, production-grade UI for any component, page, or visual interface. Handles screenshot-driven iteration when the user sends an image with a visual complaint.
- **Category**: Development
- **Author**: Tw93
- **Repository**: <a href="https://github.com/tw93/Waza" target="_blank">tw93/Waza</a>
- **Keywords**: ui, design, frontend, css, components
- **License**: MIT
- **Version**: 3.18.0
- **Installation**:
  ```bash
  /plugin install waza-design@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Waza Read

- **Name**: `waza-read`
- **Description**: Fetches any URL or PDF as clean Markdown. Handles paywalls, JS-heavy pages, X/Twitter, and Chinese platforms via proxy cascade.
- **Category**: Development
- **Author**: Tw93
- **Repository**: <a href="https://github.com/tw93/Waza" target="_blank">tw93/Waza</a>
- **Keywords**: web-fetching, pdf, markdown, content-extraction
- **License**: MIT
- **Version**: 3.14.0
- **Installation**:
  ```bash
  /plugin install waza-read@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Waza Write

- **Name**: `waza-write`
- **Description**: Strips AI writing patterns and rewrites prose to sound natural in Chinese or English. Only activates on explicit writing or editing requests.
- **Category**: Development
- **Author**: Tw93
- **Repository**: <a href="https://github.com/tw93/Waza" target="_blank">tw93/Waza</a>
- **Keywords**: writing, editing, natural-language, chinese, english
- **License**: MIT
- **Version**: 3.18.0
- **Installation**:
  ```bash
  /plugin install waza-write@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Waza Learn

- **Name**: `waza-learn`
- **Description**: Runs a six-phase research workflow to turn unfamiliar domains or collected sources into publish-ready output.
- **Category**: Development
- **Author**: Tw93
- **Repository**: <a href="https://github.com/tw93/Waza" target="_blank">tw93/Waza</a>
- **Keywords**: research, learning, workflow, writing
- **License**: MIT
- **Version**: 3.15.0
- **Installation**:
  ```bash
  /plugin install waza-learn@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Design Extract

- **Name**: `design-extract`
- **Description**: Extract the complete design language from any website — colors, typography, spacing, shadows, components, and more. Outputs AI-optimized markdown, W3C design tokens, Tailwind config, and CSS variables.
- **Category**: Design
- **Author**: Manavarya Singh
- **Repository**: <a href="https://github.com/Manavarya09/design-extract" target="_blank">Manavarya09/design-extract</a>
- **Keywords**: design-system, design-tokens, css, tailwind, typography, colors, web-scraping
- **License**: MIT
- **Version**: 1.0.0
- **Installation**:
  ```bash
  /plugin install design-extract@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Claude Flow

- **Name**: `claude-flow`
- **Description**: Enterprise AI agent orchestration plugin with 150+ commands, 74+ specialized agents, SPARC methodology, swarm coordination, GitHub integration, and neural training capabilities.
- **Category**: Development
- **Author**: rUv
- **Repository**: <a href="https://github.com/ruvnet/claude-flow" target="_blank">ruvnet/claude-flow</a>
- **Keywords**: ai-agents, swarm-intelligence, orchestration, sparc-methodology, github-automation, neural-training, mcp-integration, enterprise, workflow-automation, multi-agent
- **License**: MIT
- **Version**: 2.5.0
- **Installation**:
  ```bash
  /plugin install claude-flow@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### All Permissions

- **Name**: `all-permissions`
- **Description**: Claude Code plugin for auto-approving tool calls after security scanning for prompt injections, path traversal, and other injection attacks.
- **Category**: Security
- **Author**: adrianR84
- **Repository**: <a href="https://github.com/adrianR84/claude-code-all-permissions" target="_blank">adrianR84/claude-code-all-permissions</a>
- **Keywords**: security, permissions, auto-approve, injection-prevention, prompt-injection
- **License**: MIT
- **Version**: 1.0.2
- **Installation**:
  ```bash
  /plugin install all-permissions@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### AgentOps

- **Name**: `agentops`
- **Description**: The operational layer for coding agents. Bookkeeping, validation, and flows that compound knowledge between sessions.
- **Category**: Development
- **Author**: Boden Fuller
- **Repository**: <a href="https://github.com/boshu2/agentops" target="_blank">boshu2/agentops</a>
- **Keywords**: devops, cursor, codex, ai-agents, claude, vibe-coding, claude-code, claude-code-plugins, claude-skills, claude-marketplace, codex-plugin, opencode-plugin
- **License**: Apache-2.0
- **Version**: 2.39.0
- **Installation**:
  ```bash
  /plugin install agentops@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Last30Days

- **Name**: `last30days`
- **Description**: Research any topic across Reddit, X, YouTube, TikTok, Instagram, Hacker News, Polymarket, GitHub, and 5+ more sources. AI agent scores by upvotes, likes, and real money - not editors.
- **Category**: Productivity
- **Author**: Matt Van Horn
- **Repository**: <a href="https://github.com/mvanhorn/last30days-skill" target="_blank">mvanhorn/last30days-skill</a>
- **Keywords**: reddit, youtube, twitter, hackernews, polymarket, research, web-search, tiktok, instagram, trends
- **Version**: 3.1.1
- **Installation**:
  ```bash
  /plugin install last30days@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Understand Anything

- **Name**: `understand-anything`
- **Description**: Graphs that teach > graphs that impress. Turn any code, or knowledge base (Karpathy LLM wiki), into an interactive knowledge graph you can explore, search, and ask questions about.
- **Category**: Productivity
- **Author**: Lum1104
- **Repository**: <a href="https://github.com/Lum1104/Understand-Anything" target="_blank">Lum1104/Understand-Anything</a>
- **Keywords**: knowledge-graph, knowledge-base, codex, karpathy, wiki, memory, codebase-analysis
- **License**: MIT
- **Version**: 2.3.1
- **Installation**:
  ```bash
  /plugin install understand-anything@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

### Everything Claude Code

- **Name**: `everything-claude-code`
- **Description**: The agent harness performance optimization system. 48 agents, 182 skills, 68 command shims, TDD/security/review hooks, and research-first development for Claude Code, Codex, Cursor and beyond.
- **Category**: Development
- **Author**: Affaan Mustafa
- **Repository**: <a href="https://github.com/affaan-m/everything-claude-code" target="_blank">affaan-m/everything-claude-code</a>
- **Keywords**: agent-harness, performance-optimization, tdd, security-scanning, code-review, skills, agents, harness, anthropic-hackathon
- **License**: MIT
- **Version**: 2.0.0-rc.1
- **Installation**:
  ```bash
  /plugin install everything-claude-code@claude-code-awesome
  ```

[← Back to Available Plugins](#-available-plugins)

## 🔧 Usage

Once installed, plugins will be available in your Claude Code environment. Refer to individual plugin documentation for specific usage instructions.

## 📄 License

This marketplace configuration is licensed under the MIT License. Individual plugins may have their own licenses - please refer to their respective repositories.

## 🔗 Links

- [Claude Code Documentation](https://code.claude.com/docs)
- [Plugin Marketplace Documentation](https://code.claude.com/docs/en/plugin-marketplaces)
- [Plugin Reference](https://code.claude.com/docs/en/plugins-reference)
