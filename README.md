### Hi there 👋

This repository doubles as the **`devp0tion` Claude Code plugin marketplace** — a single catalog for the Claude Code plugins published under [DevP0tion](https://github.com/DevP0tion).

## 🧩 Plugin Marketplace

Add the marketplace once, then install any plugin from it:

```
/plugin marketplace add DevP0tion/DevP0tion
/plugin install <plugin-name>@devp0tion
```

### Available plugins

| Plugin | Description |
|--------|-------------|
| `xlmcp` | Excel automation MCP server (49 tools). Session pooling, virtual clipboard, chunked parallel I/O. Windows only. |
| `team-report` | Multi-agent team analysis producing an interactive paginated HTML report with Accept/Defer/Reject decision cards and a feedback loop. |

For example, to install the Excel MCP plugin:

```
/plugin marketplace add DevP0tion/DevP0tion
/plugin install xlmcp@devp0tion
```

Each plugin's source lives in its own repository and is mirrored here as a git
submodule under [`plugins/`](plugins/) for browsing. Installation always fetches
directly from the source repository, so you don't need to init the submodules.
