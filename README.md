# tool4seller MCP Server

Official MCP server for [tool4seller](https://www.tool4seller.com) — the all-in-one Amazon seller platform by TAPCASH INC.

Connect ChatGPT, Claude, or any MCP client to your Amazon seller data and work with it in natural language.

## What you can do

- **Store health diagnostics** — an AI-generated overview of your store's current state
- **Sales & profit analytics** — revenue, costs, fees, and profit by store, product, and ASIN
- **Advertising performance** — ACOS/ROAS analysis for Amazon Ads, with preview-confirmed ad changes
- **Inventory risk** — stockout risks and FBA inbound planning
- **Search-term performance** — keyword and search-term insights across 22 Amazon marketplaces

## Connect

- **Endpoint:** `https://das-server.tool4seller.com/mcp` (Streamable HTTP)
- **Authentication:** OAuth — sign in with your tool4seller account (the server publishes standard OAuth Protected Resource metadata). You can also connect via the ChatGPT plugin or the Claude connector.
- **Alternative:** an MCP Key issued inside tool4seller under *API & MCP & CLI → MCP* can be sent as the `TS-MCP-KEY` header.

A machine-readable description of this server is in [`server.json`](./server.json) (the same file published to the Official MCP Registry as `com.tool4seller/tool4seller-mcp`).

## About tool4seller

tool4seller is an all-in-one Amazon seller software platform — profit analytics, PPC/ads automation, keyword research, inventory and multi-store management — serving 350,000+ sellers since 2017, on Web, iOS, and Android.

- Website: https://www.tool4seller.com
- Support: support@messages.tool4seller.com

*This repository is a public descriptor for the hosted tool4seller MCP server. The server itself is a hosted service; no server code is distributed here.*
