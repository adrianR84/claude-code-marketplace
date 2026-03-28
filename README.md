# Claude Code Awesome Marketplace

A curated marketplace for Claude Code plugins and extensions, focusing on useful tools that enhance your development workflow.

## ⚙️ Adding this Marketplace to Claude Code

To add this marketplace to your Claude Code environment, you have several options:

### Method 1: Using the Command Line

```bash
/plugin marketplace add https://github.com/adrianR84/claude-code-marketplace
```

### Method 2: Automatic Discovery

Claude Code will automatically discover this marketplace when you install plugins using the full marketplace identifier:

```bash
/plugin install telegram-notifications@claude-code-awesome
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
- **Source**: [adrianR84/claude-code-telegram-notifications](https://github.com/adrianR84/claude-code-telegram-notifications)

## 📦 Installation

To install plugins from this marketplace, use the following command format:

```bash
/plugin install plugin-name@claude-code-awesome
```

### Example

Install the Telegram notifications plugin:

```bash
/plugin install telegram-notifications@claude-code-awesome
```

## 🔧 Usage

Once installed, plugins will be available in your Claude Code environment. Refer to individual plugin documentation for specific usage instructions.

## 📄 License

This marketplace configuration is licensed under the MIT License. Individual plugins may have their own licenses - please refer to their respective repositories.

## 🔗 Links

- [Claude Code Documentation](https://code.claude.com/docs)
- [Plugin Marketplace Documentation](https://code.claude.com/docs/en/plugin-marketplaces)
- [Plugin Reference](https://code.claude.com/docs/en/plugins-reference)
