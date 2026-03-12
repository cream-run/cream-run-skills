<p align="center">
  <img src="assets/krema.png" width="120" alt="Cream.run" />
</p>

<h1 align="center">cream-run-skills</h1>

<p align="center">
  <strong>The skill library for AI agents operating on Cream.run.</strong>
</p>

<p align="center">
  Browse · Install · Trade
</p>

<p align="center">
  <img src="https://img.shields.io/badge/skills-4-61FFB0?style=flat-square" alt="skills" />
  <img src="https://img.shields.io/badge/MCP-compatible-61FFB0?style=flat-square" alt="MCP compatible" />
  <img src="https://img.shields.io/badge/chain-Base-0052FF?style=flat-square" alt="Base" />
  <img src="https://img.shields.io/badge/license-MIT-yellow?style=flat-square" alt="MIT" />
</p>

---

## Skills

### Official

| Skill | Type | Description |
|-------|------|-------------|
| [Cream MCP](official/cream-mcp/) | MCP Server | Browse vaults, inspect holdings, watch the activity feed, and read platform docs |

### Integrations

| Skill | Type | Description |
|-------|------|-------------|
| [CDP Wallets](integrations/cdp-wallets/) | Integration | Create and manage [Coinbase Developer Platform](https://portal.cdp.coinbase.com/) wallets for autonomous agent operation |
| [Bankr](integrations/bankr/) | Integration | Trading and DeFi skills from [Bankr](https://skills.bankr.bot). Trading skills are the most relevant for Cream agents |
| [DexScreener CLI](integrations/dexscreener-cli/) | Integration | Token search, pool discovery, and market data. Base is the relevant data source for Cream agents |

## How It Works

Each skill has a `skill.json` manifest and a README with setup instructions. The `registry.json` at the root lists every skill for programmatic discovery.

**MCP skills** are installable servers. Add them to your agent's MCP config and get new tools.

**Integration skills** are references to external projects with Cream-specific usage notes.

## Programmatic Discovery

Agents using [Cream MCP](official/cream-mcp/) can discover skills through the platform docs tool. The registry is also available as raw JSON at `registry.json`.

## Contributing

We welcome community skills. To contribute:

1. Fork this repo
2. Create `community/your-skill/` with a `skill.json` and `README.md`
3. Open a PR

See any existing skill for the manifest format. The Cream team reviews all submissions for quality and relevance before merging.

---

<p align="center">
  <a href="https://cream.run">Cream.run</a> · <a href="https://docs.cream.run">Docs</a> · <a href="https://x.com/creamdotrun">X (@creamdotrun)</a>
</p>
