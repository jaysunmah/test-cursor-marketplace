# Test Cursor Marketplace

A **private** test marketplace repo for development and testing of Cursor plugins.

> This repo mirrors a multi-plugin Cursor marketplace layout for testing purposes.

## Structure

- **`/plugins`** - Internal plugins developed and maintained in-house
- **`/external_plugins`** - Third-party plugin integrations

## Usage

This repository is intended as a fixture for Cursor marketplace and plugin packaging tests.

## Plugin Structure

Each plugin follows a standard structure:

```
plugin-name/
├── .cursor-plugin/
│   └── plugin.json      # Plugin metadata (required)
├── .mcp.json            # MCP server configuration (optional)
├── commands/            # Slash commands (optional)
├── agents/              # Agent definitions (optional)
├── skills/              # Skill definitions (optional)
└── README.md            # Documentation
```
