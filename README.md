<!-- Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0f172a,50:1e3a8a,100:06b6d4&text=Cloudpeakify&fontColor=ffffff&fontSize=64&fontAlignY=38&desc=Product%20studio%20%C2%B7%20AI%20infrastructure%20%C2%B7%20Prague&descAlignY=60&descSize=18&animation=fadeIn" width="100%" alt="Cloudpeakify" />

<p align="center">
  <a href="https://github.com/RulezZzOr">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=06B6D4&center=true&vCenter=true&width=640&lines=Product+studio+from+Prague+%F0%9F%8F%94%EF%B8%8F;Agent+commerce+control+plane+%F0%9F%9B%92;Retries+never+double-charge+%E2%9C%85;MCP+servers+%C2%B7+Go+%C2%B7+Rust+%C2%B7+TypeScript;From+first+commit+to+production" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.cloudpeakify.com"><img src="https://img.shields.io/badge/cloudpeakify.com-0f172a?style=for-the-badge&logo=googlechrome&logoColor=06b6d4" alt="Website" /></a>
  <a href="https://ordercore.ai"><img src="https://img.shields.io/badge/ordercore.ai-1e3a8a?style=for-the-badge&logo=shopify&logoColor=white" alt="OrderCore" /></a>
  <a href="https://rea.tools"><img src="https://img.shields.io/badge/rea.tools-06b6d4?style=for-the-badge&logo=ghostery&logoColor=white" alt="rea.tools" /></a>
  <img src="https://komarev.com/ghpvc/?username=RulezZzOr&style=for-the-badge&color=0f172a&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

## 🏔️ Who we are

**Cloudpeakify s.r.o.** is a product studio from **Prague 🇨🇿**, founded by Richard Skácel.
We design, build and run our own software products — end to end, from the first commit to
production on Google Cloud. Small team, AI-native workflow, no outsourcing of the hard parts.

> We build the boring-but-critical layer underneath AI: the part that has to be **correct**
> when an agent retries, times out or loops — and real money, real data or a real network is on the line.

## ⚙️ What we do

<table>
<tr>
<td width="33%" valign="top">

**🤖 Infrastructure for AI agents**<br/>
MCP servers, tool APIs and control planes that let agents act safely in the real world —
idempotent, auditable, fail-closed.

</td>
<td width="33%" valign="top">

**🏗️ Platforms & SaaS**<br/>
Multi-tenant products on GCP: APIs, SDKs, dashboards, billing, compliance-ready operations.
From idea to a running service.

</td>
<td width="33%" valign="top">

**🛡️ Self-hosted & private-by-default**<br/>
Local-first tools that run on your own hardware — firewall, LLM routing, data that never
leaves your network.

</td>
</tr>
</table>

```yaml
company:   Cloudpeakify s.r.o.   # Prague, CZ — EU, GDPR-first
products:  [OrderCore, Coriventra, Firewator, rea.tools, Aleatoria, WanderScope]
focus:     [agentic-commerce, mcp, idempotency, self-hosted-ai, regulated-platforms]
shipping:  Go · Rust · TypeScript · Python
runs_on:   Google Cloud · Cloudflare · bare metal
belief:    "An agent is a retry machine pointed at your API."
```

## 🚀 What we've built

<table>
<tr>
<td width="50%" valign="top">

#### 🛒 [OrderCore](https://ordercore.ai)
Commerce backend **+ MCP server** for AI agents — catalog, prices, inventory and
**idempotent checkout** for Shopify & WooCommerce. Two completion calls → one order. Always.

```bash
claude mcp add ordercore -- ordercore-mcp
```

<a href="https://github.com/RulezZzOr/ordercore-examples"><img src="https://img.shields.io/badge/try%20it-30%20seconds,%20no%20signup-22c55e?style=flat-square" /></a>
<img src="https://img.shields.io/badge/MCP-server-f97316?style=flat-square" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />

</td>
<td width="50%" valign="top">

#### 🎰 [Coriventra](https://coriventra.com)
**Gaming infrastructure for regulated markets.** Not another casino — a B2B platform for
operators, aggregators and studios: remote game server, integration gateway, engagement tools,
analytics, operator & game SDKs, compliance-ready operations.

<img src="https://img.shields.io/badge/B2B-platform-8b5cf6?style=flat-square" />
<img src="https://img.shields.io/badge/regulated-markets-0f172a?style=flat-square" />
<img src="https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔥 Firewator
Free, **local-first policy engine, scheduler, DNS ad-blocker and MCP server for OPNsense.**
One-click policies, time schedules, per-device rules — and your AI client can ask the firewall
*"why does this device have no Internet, and when does it come back?"* Runs **on** the firewall:
no cloud, no telemetry, no license server.

<img src="https://img.shields.io/badge/OPNsense-d94f00?style=flat-square&logo=opnsense&logoColor=white" />
<img src="https://img.shields.io/badge/MCP-server-f97316?style=flat-square" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />

</td>
<td width="50%" valign="top">

#### 🔬 [rea.tools](https://rea.tools)
Reverse engineer anything with agents — from app behaviour all the way down to native binaries.

<br/>

<a href="https://github.com/RulezZzOr/reaMOJE"><img src="https://img.shields.io/badge/repo-reaMOJE-0f172a?style=flat-square&logo=github" /></a>
<img src="https://img.shields.io/badge/agents-reverse%20engineering-8b5cf6?style=flat-square" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🎧 Aleatoria
AI music & sound studio for **DJs, producers and sound designers** that never repeats itself:
one track with measured novelty, deterministic seed, stems, MIDI and 24-bit WAV tagged with
BPM & key for Rekordbox, Serato, Traktor and any DAW. Works offline, runs in the EU.

<img src="https://img.shields.io/badge/AI-audio-ec4899?style=flat-square" />
<img src="https://img.shields.io/badge/EU-GDPR--first-1e3a8a?style=flat-square" />

</td>
<td width="50%" valign="top">

#### 🌍 WanderScope
AI-powered **travel media company built as a reusable publishing platform** — entity graph with
provenance, ingestion, AI pipeline and retrieval, SEO and affiliate engine, with a human approval
gate before anything gets published. Live.

<img src="https://img.shields.io/badge/status-live-22c55e?style=flat-square" />
<img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" />

</td>
</tr>
</table>

**Also in the workshop:** 🧭 a self-hosted, fail-closed **LLM router** for teams that want
policy and cost control over their models · 🍵 **Matcha Ritual** — a production e-shop
(Next.js, Stripe, Prisma) for a Czech premium matcha brand · ⛏️ years of **mining & blockchain
infrastructure** — stratum servers, pool software, CUDA miners and a mining OS.

## 🧪 Open source

| Project | What it is |
| --- | --- |
| 🛒 [**ordercore-examples**](https://github.com/RulezZzOr/ordercore-examples) | Give your AI agent a retry-safe checkout tool in 5 minutes — offline, no signup |
| 🔬 [**reaMOJE**](https://github.com/RulezZzOr/reaMOJE) | Reverse engineer anything with agents, from app behaviour down to native binaries |
| 🤖 [**opensepiaRS**](https://github.com/RulezZzOr/opensepiaRS) | Autonomous AI dev team — 9 Claude agents plan sprints, code, review, test and deploy, 24/7 |
| ⛏️ [**BlockFinderPool**](https://github.com/RulezZzOr/BlockFinderPool) | Bitcoin solo-hunter node for small LAN fleets, written in Rust |
| 🐝 [**hornik**](https://github.com/RulezZzOr/hornik) | Open-source mining OS prototype for Antminer S19-class hardware |
| 📊 [**jarvis-dashboard-rs**](https://github.com/RulezZzOr/jarvis-dashboard-rs) | Obsidian dashboard for Claude Code sessions, agent fleets and 30-day analytics |

## 🛠️ Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,rust,ts,python,nodejs,react,vite,postgres,redis,docker,kubernetes,gcp,cloudflare,linux,githubactions&perline=15" alt="Tech stack" />
</p>

## 📈 Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=RulezZzOr&theme=tokyonight" width="100%" alt="Profile details" />
</p>

<p align="center">
  <img height="170" src="https://streak-stats.demolab.com/?user=RulezZzOr&theme=tokyonight&hide_border=true&background=0d1117&ring=06b6d4&fire=06b6d4&currStreakLabel=06b6d4" alt="Streak" />
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=RulezZzOr&theme=tokyonight" alt="Languages" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RulezZzOr/RulezZzOr/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RulezZzOr/RulezZzOr/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/RulezZzOr/RulezZzOr/output/github-snake-dark.svg" width="100%" />
</picture>

## 🤝 Let's talk

Building an agent that needs to buy, sell or act safely? Running a store, a gaming operation or a network
that should talk to AI? Want a product built end to end? **We want to hear from you.**

<p align="center">
  <a href="https://www.cloudpeakify.com"><img src="https://img.shields.io/badge/Get%20in%20touch-cloudpeakify.com-06b6d4?style=for-the-badge" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:06b6d4,50:1e3a8a,100:0f172a" width="100%" />
