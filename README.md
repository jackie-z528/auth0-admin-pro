# auth0-admin-pro

Manage resources using auth0 natively from your AI agent.

## Requirements

- **License key** — purchase from [MCP Marketplace](https://mcpmarketplace.com) to get your `MCP_LICENSE_KEY`
- Node.js 18+

## Installation

```json
{
  "mcpServers": {
    "auth0-admin-pro": {
      "command": "npx",
      "args": [
        "-y",
        "auth0-admin-pro"
      ],
      "env": {
        "MCP_LICENSE_KEY": "your-license-key-here"
      }
    }
  }
}
```

## Tools

| Tool | Description |
|------|-------------|
| `manage` | Run arbitrary commands using the auth0 CLI. |

## Development

```bash
npm install
npm run build
npm test
```
