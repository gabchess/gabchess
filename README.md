<div align="center">

<img src="https://github.com/gabchess.png" width="140" alt="Gabriel Abreu" />

# Gabriel Abreu

**Rio de Janeiro** · GTM Engineer · Marketing for 15 years, building for the last 5

![TypeScript](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6)
![Rust](https://img.shields.io/badge/-Rust-221e18?style=flat-square&logo=rust&logoColor=dea584)
![Solidity](https://img.shields.io/badge/-Solidity-221e18?style=flat-square&logo=solidity&logoColor=c0c0c0)
![Python](https://img.shields.io/badge/-Python-221e18?style=flat-square&logo=python&logoColor=3776AB)
![Solana](https://img.shields.io/badge/-Solana-221e18?style=flat-square&logo=solana&logoColor=14F195)
![Base](https://img.shields.io/badge/-Base-221e18?style=flat-square&logo=coinbase&logoColor=0052FF)
![Next.js](https://img.shields.io/badge/-Next.js-221e18?style=flat-square&logo=next.js&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-221e18?style=flat-square&logo=anthropic&logoColor=d4a574)

[![Portfolio](https://img.shields.io/badge/Portfolio-gabeonchain.com-d4a574?style=flat-square&labelColor=0c0a08)](https://gabeonchain.com)
[![X](https://img.shields.io/badge/X-%40gabe__onchain-221e18?style=flat-square&labelColor=0c0a08)](https://x.com/gabe_onchain)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gabeonchain-221e18?style=flat-square&labelColor=0c0a08)](https://www.linkedin.com/in/gabeonchain)

</div>

I'm Gabriel, aka Gabe. Fifteen years in product marketing, and for the last five I've been building too, mostly applied AI. Agent plumbing is where I spend most of my week.

I spot each team's gaps and bring systems to help them work better and faster. TL;DR & more deets here in [this video](https://x.com/gabe_onchain/status/2090524446826082779).

---

## 🔨 Building now

| Project | Stack | What it does |
|:--|:--|:--|
| **Tixmancer** <br/>`private · main focus` | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) ![x402](https://img.shields.io/badge/-x402-221e18?style=flat-square&logo=coinbase&logoColor=0052FF) | Event tickets bought by an agent end to end: HTTP 402 offer, signed QR ticket, one-time check-in, onchain receipt recovery on Base. 50 test files across unit, integration, contract, and browser e2e; Base Batches 004 application in. |
| **Maria** <br/>`private · milestone 1` | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) | The scam-checker Brazilian elders talk to on WhatsApp: forward anything suspicious, hear a voice verdict in PT-BR, family alerted when it matters. Building it for RevenueCat's Shipaton 2026. |

## 🎯 GTM engineering

| Project | Stack | What it does |
|:--|:--|:--|
| **[scaleflow-leads](https://github.com/gabchess/scaleflow-leads)** ⭐ | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) ![Playwright](https://img.shields.io/badge/-Playwright-221e18?style=flat-square&logo=playwright&logoColor=2EAD33) | A whole outbound lead pipeline, built in 48 hours for a trial task. Two scrapers I wrote myself (Crunchbase behind a login, Clutch), Clay enrichment driven through MCP, and 100 leads with every email checked against a live DNS MX record. Measuring the first scrape is what changed the build: 74% of the 300 Crunchbase companies had raised more than $20M against a $20M ceiling, so Clutch became the primary source. Also runs as an MCP server, with an agent that stops for human approval before any lead is marked qualified. 42 tests. [Two-minute walkthrough](https://www.loom.com/share/320038e70c3b4ba29ad5265a3e83fef3). |

## 🧩 Augments

Systems I package so someone else can run them w/o me in the room: the skills, the hooks that enforce them, and a README a stranger can follow. These two are private rn, so no links here. Ask me instead. ScaleFlow above is the one that's already out.

| Augment | What it does | Where it actually is |
|:--|:--|:--|
| **ContentOS** | 43 skills behind one front door: research, drafting, review, distribution, the weekly retro. When a write breaks a rule, a hook blocks it; nobody asks the model to remember. Btw, it carries a 770-chunk corpus of 4 studied voices, searchable offline. | Running daily. The detector pass behind it is one post on one day, and that's the only one I claim. |
| **Scribe** | The writing front door, pulled out of ContentOS so it installs on its own. Four lanes decide who arranges the sentences before any work starts. A paired reviewer suggests & never rewrites. | 24 tests green in CI. Never installed on a machine I don't control. |

## ⛓️ Solana & onchain

| Project | Lang | What it does |
|:--|:--|:--|
| **[hedwig-sol](https://github.com/gabchess/hedwig-sol)** ⭐ | ![Rust](https://img.shields.io/badge/-Rust-221e18?style=flat-square&logo=rust&logoColor=dea584) | Composable onchain roles for Solana. Grant roles, not keys. One canonical role store other Anchor programs share instead of rebuilding access control. 6 instructions, 21 LiteSVM integration tests, a documented threat model. Built on a Solana Foundation grant. |
| **[worldcup-pari-market](https://github.com/gabchess/worldcup-pari-market)** ⭐ | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) ![Rust](https://img.shields.io/badge/-Rust-221e18?style=flat-square&logo=rust&logoColor=dea584) | Proof-settled World Cup prediction markets on Solana, using TxODDS validate_stat CPI and Merkle-anchored results. Live on devnet, 39 Rust tests. [Demo](https://youtu.be/2Vh6RPLNd-U). |
| **[kageb](https://github.com/gabchess/kageb)** ⭐ | ![Rust](https://img.shields.io/badge/-Rust-221e18?style=flat-square&logo=rust&logoColor=dea584) | Private intent pooling for Solana: four real orders in, one aggregate trade out. |
| **[grimoire](https://github.com/gabchess/grimoire)** | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) | Grimoire, the Solana Transaction Doctor. Paste a failed transaction signature and it decodes the failure (Anchor errors, custom program codes, compute budget, rent, PDA collisions) into a plain-English root cause and a concrete fix. Live demo + open source. |
| **[solana-ship-gate](https://github.com/gabchess/solana-ship-gate)** | ![Shell](https://img.shields.io/badge/-Shell-221e18?style=flat-square&logo=gnu-bash&logoColor=4EAA25) | Auditor-grade pre-deploy safety gate for Solana programs: 4 deterministic checks, machine-readable PASS/FAIL, blocks unsafe mainnet deploys/upgrades via a PreToolUse hook. A Solana AI Kit skill. MIT. |
| **[patronus](https://github.com/gabchess/patronus)** | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) | Onchain-attested, runtime-scoped credentials for AI agents on Solana DeFi. |
| **[worldcup-settlement](https://github.com/gabchess/worldcup-settlement)** | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) | An AI agent that bets on live World Cup matches on Solana, autonomously. |
| **[meteora-jup-sol-safety-monitor](https://github.com/gabchess/meteora-jup-sol-safety-monitor)** | ![JS](https://img.shields.io/badge/-JavaScript-221e18?style=flat-square&logo=javascript&logoColor=F7DF1E) | Read-only Meteora DLMM PnL and safety monitor with Telegram alerts. |
| **[solguard](https://github.com/gabchess/solguard)** | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) | Warns Solana users before they get rugged. Scores new pump.fun launches on deployer history, liquidity and mint authority, then posts the risk live. |
| **[superteam-academy](https://github.com/gabchess/superteam-academy)** | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) | Open-source gamified learning for Solana devs, built for Superteam Brazil. Browser code editor, XP, leaderboards and onchain certificates. |

## 🤖 Agents & AI tooling

| Project | Lang | What it does |
|:--|:--|:--|
| **[silvia](https://github.com/gabchess/silvia)** | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) | A confirmation-first food-ordering assistant for older adults, built on Base44. Chat instead of learning an app; 50+ users completed an order. |
| **[safeskill](https://github.com/gabchess/safeskill)** | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) | One-click security audit for your MCP setup. One score, plain English, no CLI knowledge required. |
| **[wingman](https://github.com/gabchess/wingman)** | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) | AI Expert Marketplace. Install experts (Design, Code, Marketing) into Claude Code. |
| **[clawmanship](https://github.com/gabchess/clawmanship)** | ![JS](https://img.shields.io/badge/-JavaScript-221e18?style=flat-square&logo=javascript&logoColor=F7DF1E) | Reviewable decision before a community skill enters a local bundle. |
| **[agenthub](https://github.com/gabchess/agenthub)** | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) | Monad-native AI agent orchestration platform. |
| **[hermes-aria-theme](https://github.com/gabchess/hermes-aria-theme)** | ![YAML](https://img.shields.io/badge/-YAML-221e18?style=flat-square&logo=yaml&logoColor=cb171e) | Minimalist black and white dashboard theme for the Hermes agent. Green for success, red for errors, nothing else. Greek-inspired, with the Omega on every session card. |

## 🔗 EVM & multichain

| Project | Lang | What it does |
|:--|:--|:--|
| **[walletbrief-monad](https://github.com/gabchess/walletbrief-monad)** | ![Solidity](https://img.shields.io/badge/-Solidity-221e18?style=flat-square&logo=solidity&logoColor=c0c0c0) | Persistent Monad wallet briefs with human-approved, revoke-only EIP-7702 execution. |
| **[yieldpilot](https://github.com/gabchess/yieldpilot)** | ![TS](https://img.shields.io/badge/-TypeScript-221e18?style=flat-square&logo=typescript&logoColor=3178C6) | Your AI copilot for cross-chain yield optimization. Built for the Chainlink Convergence Hackathon 2026. |

## 📊 Data & analysis

| Project | Lang | What it does |
|:--|:--|:--|
| **[beat-claude-engineer-004-analytics-pipeline](https://github.com/gabchess/beat-claude-engineer-004-analytics-pipeline)** | ![Python](https://img.shields.io/badge/-Python-221e18?style=flat-square&logo=python&logoColor=3776AB) | Real-time analytics pipeline design for the Beat Claude engineer-004 challenge: fixture anomaly detector, test suite, hot-path benchmark, and doc/evidence consistency checks. |
| **[ecommerce-sales-analysis](https://github.com/gabchess/ecommerce-sales-analysis)** | ![Python](https://img.shields.io/badge/-Python-221e18?style=flat-square&logo=python&logoColor=3776AB) | E-commerce sales analysis with Python (pandas, matplotlib) and SQL. RFM segmentation, revenue trends, product performance. |
| **[solana-narrative-tracker](https://github.com/gabchess/solana-narrative-tracker)** | ![JS](https://img.shields.io/badge/-JavaScript-221e18?style=flat-square&logo=javascript&logoColor=F7DF1E) | Spots emerging Solana narratives early. Reads 20+ KOLs, 20+ repos and 25+ protocol TVLs, clusters the signals, and ships build ideas every fortnight. |
| **[defillama-tvl-anomaly-detector](https://github.com/gabchess/defillama-tvl-anomaly-detector)** | ![Python](https://img.shields.io/badge/-Python-221e18?style=flat-square&logo=python&logoColor=3776AB) | Scans DeFi protocols for TVL that looks wrong. Zeroed, dropped 50% in a day, spiked 300%, or flat for 60 days. Catches broken adapters, exploits and depegs. |

Also: [atelier-gabriel-paz](https://github.com/gabchess/atelier-gabriel-paz). A landing page I built for my friend Gabriel Paz, a painter in Botafogo, Rio. He had no website, so I made him one. Hand-written HTML, no build step.

Off GitHub: a six-agent system runs my daily marketing operations, research, drafts, review, planning, with a human sign-off at every step. 27 of 30 content cycles held above my quality threshold, and the daily brief hit 97% accuracy across 31 traced runs.

## 🔍 Security research

A high-severity find in Anchor's LazyAccount code, v0.31.0 to v0.32.1: `Lazy::size_of` on `[T; N]` measured the first element and multiplied by N, so for arrays of unsized types every field after the array loaded from the wrong byte offset and `exit()` wrote it back corrupted. [My writeup, PoC and proposed fix](https://github.com/gabchess/anchor/pull/1). Upstream landed [the same iterate-per-element fix](https://github.com/otter-sec/anchor/pull/4319) five weeks later. Bounty paid. Also the Solana Vault Standard Extension, built for a Superteam Brazil bounty: 4,398 lines of code across 34 instructions. The SVS-7 submission was the reviewer's pick of its round before losing to a full-stack entry.

> [!NOTE]
> A second finding, a fund-lockup path in Ern Protocol, was approved and paid through Immunefi. Other reports are still under review. I don't publish details of an open or rejected report; program terms exist for a reason.

## 📈 Marketing, measured

The only account that's mine alone is @gabe_onchain: 0 to 5K followers under a content rev-share, 1K+ of them verified.

Every other number here was a team run, sooo the verb is helped. Helped grow @octantapp to 13K followers & 9M organic impressions in nine months, nothing paid. Same story at InceptionLRT (past 30K) and Ankr (past 300K): I ran strategy and distribution, other people posted asw.

The Octant work I'd defend in any room is the analytics. I built their first user analytics stack, and the migration campaign built on it moved 91.9% of active allocators, 260 wallets, from V1 to V2.

At noder. I was the only product marketer for 18 months. 100+ onboarding experiments, one buyer type per test.

## ✍️ Writing

I write about proof, evals, and AI-assisted marketing at [gabeonchain.com](https://gabeonchain.com/blog.html).

- [Marketing has a proof problem](https://gabeonchain.com/posts/marketing-has-a-proof-problem.html)
- [How I stopped winging it on evals](https://gabeonchain.com/posts/how-i-stopped-winging-it-on-evals.html)
- [Keep the judgment, cut the slop](https://gabeonchain.com/posts/keep-the-judgment-cut-the-slop.html)
- [The fence is the job](https://gabeonchain.com/posts/the-fence-is-the-job.html)

## Find me

[gabeonchain.com](https://gabeonchain.com) · [X @gabe_onchain](https://x.com/gabe_onchain) · [LinkedIn](https://www.linkedin.com/in/gabeonchain)

---

<div align="center"><sub>The best systems I run live in the body, mind & soul ツ</sub></div>
