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
- **Repository**: [adrianR84/claude-code-telegram-notifications](https://github.com/adrianR84/claude-code-telegram-notifications)
- **Keywords**: telegram, notifications, hooks
- **Installation**:
  ```bash
  /plugin install telegram-notifications@claude-code-awesome
  ```

### Toast Notifications

- **Name**: `toast-notifications`
- **Description**: Windows toast notifications for Claude Code events using native Windows APIs
- **Category**: Development
- **Repository**: [TianqiZhang/claude-code-toast](https://github.com/TianqiZhang/claude-code-toast)
- **Keywords**: windows toast, notifications
- **Installation**:
  ```bash
  /plugin install toast-notifications@claude-code-awesome
  ```

## Usage

Once installed, plugins will be available in your Claude Code environment. Refer to individual plugin documentation for specific usage instructions.

## 📄 License

This marketplace configuration is licensed under the MIT License. Individual plugins may have their own licenses - please refer to their respective repositories.

## 🔗 Links

- [Claude Code Documentation](https://code.claude.com/docs)
- [Plugin Marketplace Documentation](https://code.claude.com/docs/en/plugin-marketplaces)
- [Plugin Reference](https://code.claude.com/docs/en/plugins-reference)
