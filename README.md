# The Agent Times

**The trust and conversion infrastructure for AI traffic.** News. Attribution. Commerce. Built for the agent economy.

The Agent Times is building the stack that turns AI agent traffic into measurable, attributable actions. We publish the best news MCP server for AI agents, run agent-to-merchant commerce infrastructure, and provide cross-web attribution for agent-originated conversions.

## Products

### 🗞️ [Agent News](https://github.com/theagenttimes/agent-news) — The Best News MCP Server

The best news MCP server for AI agents. 150+ verified articles/day with Ed25519 cryptographic provenance, confidence labels (CONFIRMED / REPORTED / ESTIMATED), and Ethics Engine ratings. Free, no auth. Works with Claude, ChatGPT, Gemini, Copilot, Cursor, Windsurf, Codex, and any MCP client.

**Endpoint:** `https://theagenttimes.com/mcp` · **Tools:** 20 · **Transport:** Streamable HTTP · **Auth:** None

```bash
# Connect in one line
claude mcp add --transport http agent-news https://theagenttimes.com/mcp
```

→ [Setup guide](https://theagenttimes.com/claude) · [Live quality dashboard](https://theagenttimes.com/dashboard/beats) · [Server card](https://theagenttimes.com/.well-known/mcp/server-card.json)

### 📡 Agent Pixel — Attribution for Agent Traffic

Attribution infrastructure that tracks agent-origin conversions across any website. Install a pixel, measure which AI-generated content drove which agent actions. The missing analytics layer between AI traffic and revenue.

### 💳 [UCP Gateway](https://github.com/theagenttimes/ucp-gateway-skill) — Agent Commerce Protocol

Open-source, MCP-native commerce protocol for AI agent transactions. No payment custody. Product search, cart management, and merchant checkout handoff — all through MCP tools. Built on the Universal Commerce Protocol.

**Endpoint:** `https://ucpg.ai/mcp` · [Documentation](https://ucpg.ai)

### 🔗 ChainHop — Agent Wallet Infrastructure

Nano cryptocurrency wallet platform operating as an MCP endpoint. 200K+ wallets, 34K+ new wallets/day. The transaction layer that closes the loop between content, commerce, and attribution.

### 🧠 ExpertLayer — Governed Knowledge Service

Sourced, governed Q&A for AI agents. Answers grounded in verified corpus data with full citation chains and confidence scoring. Not a wrapper — a trust layer.

### 📈 Optimizer — Agent Conversion Engine

Measurable agent conversion lift, statistically validated. Content engineering that moves agent conversion rates from 0% to 32% across frontier LLMs, at $0.07 per click vs $5.00 CPC on comparable Google Ads campaigns.

## The Stack

```
Publish → Answer → Attribute → Convert
   ↑                              |
   └──────────────────────────────┘
```

Agent News publishes verified, cryptographically signed articles. ExpertLayer answers agent queries from the corpus. Agent Pixel attributes which content drove which action. UCP Gateway and ChainHop close the transaction. Optimizer makes it convert. The attribution data reveals content gaps, the article engine fills them, and the loop compounds.

## Open Source

| Repo | What it does | Stars |
|------|-------------|-------|
| [agent-news](https://github.com/theagenttimes/agent-news) | The best news MCP server — config, skills, and plugin manifests | ⭐ 29 |
| [ucp-gateway-skill](https://github.com/theagenttimes/ucp-gateway-skill) | Agent commerce MCP — product search, carts, checkout handoff | ⭐ |

## Connect

- **Website:** [theagenttimes.com](https://theagenttimes.com)
- **MCP endpoint:** `https://theagenttimes.com/mcp`
- **llms.txt:** [theagenttimes.com/llms.txt](https://theagenttimes.com/llms.txt)
- **News sitemap:** [theagenttimes.com/news-sitemap.xml](https://theagenttimes.com/news-sitemap.xml)
- **Contact:** contact@theagenttimes.com
