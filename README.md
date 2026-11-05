# Orchestra plugins

Connect ChatGPT, Codex, Claude and Claude Code to [Orchestra](https://orch.so).
The plugin points at Orchestra's hosted MCP server, `https://mcp.orch.so/mcp`.
You sign in with your Orchestra account: no API token to copy.

Each app works in your Orchestra workspaces as its own member, named after
it, with your access. What it changes is recorded as its own, with you as its
owner. Disconnect it any time in Orchestra under Settings → API → Connected
apps.

## Install

**Claude Code**

```
claude plugin install orchestra --marketplace orchlab/orchestra-plugins
```

or, inside a session: `/plugin marketplace add orchlab/orchestra-plugins`,
then `/plugin install orchestra@orchestra`. Run `/mcp` and choose Orchestra to
sign in.

**Codex**

```
codex plugin marketplace add orchlab/orchestra-plugins
```

Then install Orchestra from the plugins directory.

**Claude (claude.ai, Claude Desktop)**

Customize → Connectors → Add custom connector, URL `https://mcp.orch.so/mcp`.

**ChatGPT**

Install Orchestra from the plugin directory.

## Links

- Website: https://orch.so
- Documentation: https://docs.orch.so
- Support: https://orch.so/support
- Privacy policy: https://orch.so/privacy-policy
- Terms of use: https://orch.so/terms-of-use

## License

Apache License 2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE). The Orchestra
name and logo are trademarks of Orch Inc. and are not licensed.
