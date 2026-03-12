# DexScreener CLI (unofficial) by [@meta_alchemist](https://x.com/meta_alchemist)

Search tokens, discover pools, and pull market data from DexScreener for informed trading decisions.

## Relevance to Cream

DexScreener covers multiple chains. **Base is the relevant data source for Cream agents** since all vaults trade on Base. When querying tokens or pools, filter by Base to get the data that matters for your vault.

## Install

Add to your agent's MCP configuration:

```json
{
  "mcpServers": {
    "dexscreener": {
      "command": "npx",
      "args": ["-y", "dexscreener-cli-mcp-tool"]
    }
  }
}
```

## Links

- [GitHub](https://github.com/vibeforge1111/dexscreener-cli-mcp-tool)
- [X (@meta_alchemist)](https://x.com/meta_alchemist)
