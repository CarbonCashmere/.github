<div align="center">

# Carbon &amp; Cashmere

**Crypto Intelligence MCP Server — built for AI agents.**

[![MCP tools](https://img.shields.io/badge/MCP-104%20tools-2563eb?style=flat-square)](https://api.carbon-cashmere.de/mcp/sse)
[![x402 native](https://img.shields.io/badge/x402-native-7c3aed?style=flat-square)](https://x402.org)
[![Networks](https://img.shields.io/badge/networks-Base%20·%20Solana%20·%20Algorand%20·%20Stellar-22c55e?style=flat-square)](https://api.carbon-cashmere.de/api/v3/x402/discover)
[![License](https://img.shields.io/badge/license-MIT-737373?style=flat-square)](https://github.com/CarbonCashmere/carbon-cashmere-mcp/blob/main/LICENSE)

`104 tools · 116 coins · 730 days history · sub-50ms latency · 4 payment networks`

[**Live Docs**](https://api.carbon-cashmere.de/docs) · [**MCP Server**](https://github.com/CarbonCashmere/carbon-cashmere-mcp) · [**Python SDK**](https://github.com/CarbonCashmere/carbon-cashmere-python) · [**Website**](https://www.carbon-cashmere.de)

</div>

---

## What we ship

Carbon &amp; Cashmere is a **node-backed crypto intelligence platform** built for AI agents, quants, and trading desks. We operate our own blockchain nodes and run a five-model XGBoost ensemble for ML signals — then expose everything as 104 MCP tools, 70+ REST endpoints, and a typed Python SDK.

**Own infrastructure, not aggregator-layer:**

- BTC mempool node · ETH beacon node · Kaspa node · Bittensor node
- 730 days of clean OHLCV across 116 coins
- Redis-cached intelligence feed — sub-50 ms on hot endpoints
- Five-model XGBoost ensemble + V3 `tsfresh` per-coin models

## Capabilities

| Pillar | What you get |
|---|---|
| **Market Data** | Real-time prices, OHLCV, gas, stablecoins (free tier available) |
| **ML Signals** | 5-model ensemble · V3 `tsfresh` per coin · conviction scoring · signal feed |
| **Intelligence Feed** | Multi-coin Redis snapshots &lt;50 ms · 730 d history |
| **Derivatives** | Funding rates · OI · long/short ratios · liquidations · options |
| **On-Chain** | BTC mempool · ETH beacon · Kaspa · Bittensor · CDD · UTXO |
| **Analytics** | HMM market regime · anomaly detection · correlation · factor analysis |
| **AI Briefings** | LLM-grounded market intelligence, sourced from live data |

## Pricing

| Tier | Cost | Best for |
|---|---|---|
| **Free** | $0 | Six endpoints, rate-limited. Try before you pay. |
| **x402** | $0.003 – $0.50 / call | Pay-per-call USDC. Best for autonomous agents. |
| **Pro** | $9.99 / month | Unlimited via API key. Best for daily workflows. |

No subscription gates the free tier. Pay-per-call requires no signup — just a wallet.

## Connect

| Surface | URL |
|---|---|
| MCP SSE | `https://api.carbon-cashmere.de/mcp/sse` |
| Smithery | [`carboncashmere/carbon-cashmere`](https://smithery.ai/server/carboncashmere/carbon-cashmere) |
| REST API docs | https://api.carbon-cashmere.de/docs |
| x402 discovery | https://api.carbon-cashmere.de/api/v3/x402/discover |
| Python SDK | `pip install carbon-cashmere` |

## Repositories

| Repo | What it is |
|---|---|
| [**carbon-cashmere-mcp**](https://github.com/CarbonCashmere/carbon-cashmere-mcp) | The MCP server — 104 tools, Docker, hosted at `api.carbon-cashmere.de` |
| [**carbon-cashmere-python**](https://github.com/CarbonCashmere/carbon-cashmere-python) | Python SDK — 39 methods across 70+ endpoints |
| [**awesome-x402**](https://github.com/CarbonCashmere/awesome-x402) | Curated x402 protocol resources |

## Built on

- [Model Context Protocol](https://modelcontextprotocol.io) — Anthropic's open standard for tool use
- [x402](https://x402.org) — HTTP 402 payments protocol (Coinbase + Linux Foundation)
- 11 x402 facilitators — CDP · Dexter · PayAI · Questflow · Bitrefill · OpenX402 · 0xArchive · 0xMeta · AutoIncentive · GoPlausible · OZ

## Listings

[![Smithery verified](https://img.shields.io/badge/Smithery-verified-22c55e?style=flat-square)](https://smithery.ai/server/carboncashmere/carbon-cashmere)
[![Glama listed](https://img.shields.io/badge/Glama-listed-22c55e?style=flat-square)](https://glama.ai)
[![CDP Bazaar](https://img.shields.io/badge/CDP%20Bazaar-100%2B%20routes-22c55e?style=flat-square)](https://api.cdp.coinbase.com/platform/v2/x402/discovery/resources)
[![402index.io](https://img.shields.io/badge/402index.io-claimed-22c55e?style=flat-square)](https://402index.io)

---

<sub>Carbon &amp; Cashmere is operated by **ChainScore Trust GmbH**. © 2025–2026 · [Website](https://www.carbon-cashmere.de) · [Docs](https://api.carbon-cashmere.de/docs)</sub>
