# Informus plugins for Claude

Plugins from [Informus](https://www.informus.ai) for Claude and Claude Code.

| Plugin | What it does |
|---|---|
| [`informus-flow`](plugins/informus-flow) | Informus Flow in Claude: what's waiting on you, your priorities and work packages, capturing thoughts, and building from a package. Runs on your own Claude plan. |

## Install

**In Claude Code:**

```bash
claude plugin marketplace add jlee462/informus-plugins
claude plugin install informus-flow@informus
```

**For everyone in a company (Claude Team or Enterprise):** an Owner adds this marketplace once,
`jlee462/informus-plugins`, and sets **informus-flow** to *Installed by default* or *Required*:

- claude.ai: Organization settings → Plugins & skills.
- Claude Code: managed settings, with this repository under `extraKnownMarketplaces` and
  `"informus-flow@informus": true` under `enabledPlugins`.

Each person signs in to Informus Flow themselves the first time. The plugins carry no keys or data.
