# DB Inspector MCP

A Cursor plugin fixture that demonstrates the `mcpServers` optional manifest field.

## Included Components

- A plugin manifest with `"mcpServers": ".mcp.json"`
- A local `.mcp.json` file using the documented `mcpServers` shape
- One skill and one command focused on read-only database inspection

## Structure

```text
db-inspector-mcp/
├── .cursor-plugin/
│   └── plugin.json
├── .mcp.json
├── commands/
├── skills/
└── README.md
```
