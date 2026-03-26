# SuiOracle MCP Server

**9 DeFi risk & compliance intelligence tools for the Sui ecosystem.**

Move language, object-centric model, $590M TVL — Sui's DeFi ecosystem needs risk intelligence.

## Live Endpoint

```
https://tooloracle.io/sui/mcp/
```

No API key required. MIT licensed.

## Quick Setup

```json
{
  "mcpServers": {
    "suioracle": {
      "url": "https://tooloracle.io/sui/mcp/"
    }
  }
}
```

## Tools (9)

| Tool | Description | Data Source |
|------|-------------|------------|
| `sui_overview` | Sui ecosystem: SUI price, TVL, validators, epoch, total transactions | CoinGecko + DeFiLlama + Sui RPC |
| `sui_protocol_health` | Protocol health: TVL, audits, risk grade (Cetus, NAVI, Scallop, Bluefin...) | DeFiLlama |
| `sui_object_info` | Get Sui object details by ID (type, owner, version, digest) | Sui RPC |
| `sui_defi_yields` | Compare DeFi yields across Sui protocols | DeFiLlama Yields |
| `sui_protocol_list` | All Sui DeFi protocols ranked by TVL | DeFiLlama |
| `sui_stablecoin_risk` | Stablecoin supply and risk on Sui | DeFiLlama |
| `sui_dex_volume` | DEX volume across Sui exchanges | DeFiLlama DEX |
| `sui_validator_info` | Validator overview: count, stake, top 10, commission rates, APY | Sui RPC |
| `sui_bridge_flows` | Bridge flow monitoring | DeFiLlama Bridges |

## Data Sources

- **Sui RPC** (fullnode.mainnet.sui.io) — Objects, validators, epoch, transactions
- **DeFiLlama** — TVL, yields, stablecoins, DEX volumes, bridges
- **CoinGecko** — Prices, market data

## Links

- **Live endpoint**: https://tooloracle.io/sui/mcp/
- **Health check**: https://tooloracle.io/sui/health
- **Builder**: [FeedOracle Technologies](https://feedoracle.io) — EU-based compliance infrastructure
- **Marketplace**: [ToolOracle](https://tooloracle.io)
- **License**: MIT
