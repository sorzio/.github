<div align="center">
  <a href="https://www.sorzio.com">
    <img src="https://raw.githubusercontent.com/sorzio/sorzio-mcp/main/assets/banner.png" alt="Sorzio: Send Your AI to Work on 25,000 Leads" width="100%" />
  </a>

  <br />

  <p>
    <a href="https://github.com/sorzio/sorzio-mcp"><img src="https://img.shields.io/badge/MCP_Server-sorzio.com%2Fapi%2Fmcp-05429E?style=for-the-badge" alt="MCP Server" /></a>
    <a href="https://github.com/sorzio/sorzio-mcp"><img src="https://img.shields.io/badge/Tools-41_Core_%2B_6_Decide-2563EB?style=for-the-badge" alt="41 Core + 6 Decide Tools" /></a>
    <a href="https://www.sorzio.com/#pricing"><img src="https://img.shields.io/badge/BYOK-0%25_Markup_on_Pro-16A34A?style=for-the-badge" alt="0% BYOK Markup" /></a>
    <a href="https://workspace.google.com/marketplace/app/replylabs_ai_verify_scrape_for_sheets/860378915175"><img src="https://img.shields.io/badge/Google_Sheets-Add--On-0F172A?style=for-the-badge" alt="Google Sheets Add-On" /></a>
  </p>

  <p>
    <a href="https://www.sorzio.com"><strong>sorzio.com</strong></a> ·
    <a href="https://github.com/sorzio/sorzio-mcp"><strong>sorzio-mcp</strong></a> ·
    <a href="https://www.sorzio.com/mcp"><strong>MCP Docs</strong></a> ·
    <a href="https://www.sorzio.com/claude"><strong>Claude Setup</strong></a> ·
    <a href="https://workspace.google.com/marketplace/app/replylabs_ai_verify_scrape_for_sheets/860378915175"><strong>Sheets Add-On</strong></a> ·
    <a href="https://www.sorzio.com/llms-full.txt"><strong>llms-full.txt</strong></a>
  </p>
</div>

---

### Server-Side Outbound &amp; GTM Execution for AI Agents and Google Sheets

**Sorzio** lets you refine prompts and ICP rubrics on **3, 10, or 50 sample rows** inside Claude or ChatGPT, then executes across up to **25,000 B2B leads** in Hosted Lists or directly inside **Google Sheets** while charging **only succeeded rows**.

<p align="center">
  <img src="https://raw.githubusercontent.com/sorzio/sorzio-mcp/main/assets/architecture.png" alt="Sorzio Architecture" width="100%" />
</p>

### Connect in 30 Seconds (`OAuth 2.1 + PKCE`)

```bash
claude mcp add --transport http sorzio https://www.sorzio.com/api/mcp
```

Or add `https://www.sorzio.com/api/mcp` under **Settings -> Connectors** in **Claude.ai**, **Claude Desktop**, or **ChatGPT**, or drop `.mcp.json` into **Cursor / Windsurf / VS Code** (see [`sorzio/sorzio-mcp`](https://github.com/sorzio/sorzio-mcp)).

### Core Capabilities at a Glance

| Pillar | What Runs Server-Side | Transparent Rate |
| :--- | :--- | :--- |
| **Email Verification** | 5 mailbox verdicts (`deliverable`, `undeliverable`, `catch_all`, `risky`, `unknown`) + `$0` Flow checkpoint | **`$0.01 / email`** (`$10 / 1k`) |
| **6-Page Web + LinkedIn** | Default 6-page company crawl (`$0` subpages + auto-rescue), Jina, Firecrawl JS, LinkedIn `/company/` &amp; `/in/` | **`$0.006`** Web · **`$0.0075`** Co · **`$0.01`** `/in/` |
| **3 AI Modes (300+ Models)** | Calibrated `typesafe-ai/jev-1.14.0` Decision Mode, 5-provider Live Web Search, Generative + Self-Healing Copy | **`$1 / 1k`** Decide · **`0%` BYOK on Pro (`$39/mo`)** |
| **DAG Flows &amp; Schedules** | 5 checkpoint types (`keep` / `reject` / `unsure`), 16-role `column_intelligence`, daily/weekly/monthly Sheet crons | Test **3, 10, or 50 rows** safely first |
| **1:1 Prospect Microsites** | 4 executive outbound page archetypes + bot-filtered human dwell &amp; CTA analytics + optional Custom CNAME | **`$0.00` publish** · **`$0.15`** first human open |

### Public Repositories

- **[`sorzio/sorzio-mcp`](https://github.com/sorzio/sorzio-mcp)**: Official Remote MCP Server manifest (`server.json`, `.mcp.json`), 47-tool reference, architecture diagrams, and 6 agent skills (`sorzio-quickstart`, `sorzio-flow-builder`, `sorzio-lead-research`, `sorzio-icp-qualification`, `sorzio-email-verification`, `sorzio-check-results`).

<sub>Built by <strong>Empra Consultancy LTD</strong> (<a href="mailto:hello@sorzio.com">hello@sorzio.com</a> · <a href="https://www.sorzio.com">sorzio.com</a>). Independent product; not affiliated with Reply.io. Up to <strong>$20 free welcome credit</strong> on sign-up.</sub>
