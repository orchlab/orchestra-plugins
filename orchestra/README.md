# Orchestra plugin

Connects ChatGPT, Codex, Claude and Claude Code to Orchestra's hosted MCP
server, `https://mcp.orch.so/mcp`. Signing in uses OAuth through
`https://auth.orch.so`; nobody copies an API token.

Each app works in Orchestra as **its own member** (a connected-app bot named
after it: ChatGPT, Claude, …) with **its owner's access**: what it does is shown
as its own, with the person who connected it as its owner. People manage their
connections in Settings → API → Connected apps, and disconnecting one stops it
at once.

## Install

- **Claude Code:** `claude plugin install orchestra --marketplace orchlab/orchestra-plugins`,
  or add the server directly:
  `claude mcp add --transport http orchestra https://mcp.orch.so/mcp`.
- **Codex:** `codex plugin marketplace add orchlab/orchestra-plugins`, then install
  Orchestra from the plugins directory in the ChatGPT desktop app.
- **Claude (claude.ai, Desktop):** Settings → Connectors → Add custom connector,
  `https://mcp.orch.so/mcp`. Listed through Anthropic's connector directory.
- **ChatGPT:** from the plugin directory once listed; until then, developer
  mode → Create, with the same URL and OAuth.
