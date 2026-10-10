# Ziply plugin

The Ziply plugin for Claude and ChatGPT. It finds what to write from
your Ziply topic queue, writes blog posts, pages, eBooks, social posts and Reddit discussions in
your brand's voice, and saves them to Ziply Content Factory as drafts. It never publishes.

## Install

**Claude desktop app:** Settings → Plugins → Add marketplace → enter
`ZplyAI/ziply-mcp-plugin` → Sync, then install **ziply**.

**Claude Code:**

```bash
claude plugin marketplace add ZplyAI/ziply-mcp-plugin
claude plugin install ziply@ziply
```

**ChatGPT desktop app (Work or Codex):** add `ZplyAI/ziply-mcp-plugin` as a plugin marketplace,
then install **Ziply**.

Then connect Ziply when asked (in Claude Code: `/mcp` → `ziply` → Authenticate) and sign in with
your Ziply account. Ask "Is Ziply connected?" to check.

## What's inside

```
CAPABILITIES.md                    what the plugin can do, for customers
.claude-plugin/marketplace.json    lists the plugin, so this repo can be added as a marketplace
.agents/plugins/marketplace.json   the same, for ChatGPT
plugins/ziply/
├── .claude-plugin/plugin.json     plugin name, version and description
├── .mcp.json                      the Ziply connection (MCP server URL)
├── plugin.json, mcp.json          the same, for ChatGPT
├── assets/icon.png                ChatGPT icon
├── skills/                        7 skills: setup, find topics, brief, long-form, social, Reddit, save
└── commands/                      /ziply:status, topics, brief, social, reddit, push
```

See [CAPABILITIES.md](CAPABILITIES.md) for everything the plugin can do, what it needs, and what's not
in this release.
