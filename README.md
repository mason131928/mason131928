<div align="center">

<img src="./assets/mason-banner.svg" width="100%" alt="Mason Hsu — Product Builder / Founder Mode" />

<br />

**0→1 PRODUCT** · **AI-NATIVE SYSTEMS** · **VENTURE EXPERIMENTS** · **TAIPEI, TAIWAN 🇹🇼**

</div>

## 01 / I build from 0 → 1

<img align="right" width="390" src="./assets/mason-builder-loop.svg" alt="Mason Product OS" />

I'm **Mason Hsu** — a product builder with a founder's bias.

I like staying close to the whole loop: **find an uncomfortable problem, define the smallest useful wedge, prototype the product and architecture together, ship it, then learn from users, latency, cost, reliability, and economics.**

I use code as a product-thinking tool. The goal is not to collect frameworks; the goal is to turn ambiguity into something people can actually use.

- **Product** — problem framing, PRDs, UX, scope, pricing, GTM, experiments
- **AI** — agents, tool use, evals, realtime, multimodal, local inference
- **Systems** — edge/cloud architecture, data, queues, realtime state, observability
- **Founder mode** — unit economics, failure modes, privacy, safety, distribution

> **The question I keep coming back to:** what becomes possible when AI is part of the product architecture — not a chat box bolted on at the end?

<br clear="right" />

<br />

<img src="./assets/build-spectrum.svg" width="100%" alt="Build spectrum across local AI, realtime, evidence systems, interactive products, SaaS and hardware" />

---

## 02 / Flagship builds

These are the projects that best represent how I think about products and systems.

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [HashAgent](https://github.com/mason131928/hashagent)

<sub>LOCAL AI · OPEN SOURCE · LIVE</sub>

**Share an AI agent as a URL.**

A browser-first agent product where the agent definition can live in the URL and inference runs locally through WebGPU. No inference server, no account, and no tracking are required for the core experience.

**Product bet:** useful AI does not always need a backend inference service.

`WebGPU` `WebLLM` `Transformers.js` `Cloudflare`

**[Try it →](https://hashagent.pages.dev)** · **[Source →](https://github.com/mason131928/hashagent)**

</td>
<td width="50%" valign="top">

### 🧧 [月老值班中](https://imyuelao.com)

<sub>INTERACTIVE PRODUCT · 3D · REALTIME · LIVE</sub>

**A multiplayer 3D world built around the lifecycle of a wish.**

Six stylized Taiwanese temple worlds combine first/third-person exploration, realtime rooms, interactive storytelling, wish workflows, and AI-assisted content.

**Product bet:** cultural rituals can become playable digital systems without collapsing the experience into a chatbot.

`React` `R3F` `Hono` `D1` `R2` `Durable Objects` `Workers AI`

**[Enter the world →](https://imyuelao.com)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📚 [SAGE](https://github.com/mason131928/SAGE)

<sub>AI SYSTEMS · EVIDENCE · OPEN SOURCE</sub>

**Semantic Agentic Generation Engine.**

An evidence-first report-generation system for qualitative and mixed-method datasets, built around layered full-dataset synthesis, reviewable artifacts, retrieval, evaluation, and operational control.

**Product bet:** serious AI output needs traceability and evaluation — not just a thin retrieval slice.

`Agents` `Evaluation` `Retrieval` `Node.js` `SQLite`

**[View source →](https://github.com/mason131928/SAGE)**

</td>
<td width="50%" valign="top">

### 🦉 MemOwl

<sub>REALTIME AI · MEETING AGENT · PRIVATE BUILD</sub>

**A realtime meeting AI agent designed from the constraints backward.**

Before treating the app as “done,” the build explicitly models provider quality, meeting unit cost, latency, backup/restore, privacy, release readiness, and realtime voice paths.

**Product bet:** realtime agents are latency / cost / reliability products, not prompt demos.

`Realtime` `Voice` `TypeScript` `Benchmarks` `Quality Gates`

</td>
</tr>
</table>

---

## 03 / Venture lab

Not every idea should become a company. I like building small, real experiments that test a **wedge, constraint, or business model** before over-investing.

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ SafeBack

<sub>PHYSICAL COMPUTING · SAFETY · EARLY PROTOTYPE</sub>

A clip-on rear-vehicle warning concept for pedestrians, runners, roadside workers, and later riders. It explores mmWave radar, acoustic pre-warning, IMU filtering, TTC classification, haptic alerts, BLE, firmware, and a mobile shell.

**Constraint being tested:** can a safety product work locally, privately, and without depending on a phone or network for its core warning loop?

`ESP32-S3` `mmWave` `BLE` `C++` `React Native`

</td>
<td width="50%" valign="top">

### 🏠 Housebook

<sub>MICRO-SAAS · AUTOMATION · MONETIZATION</sub>

An AI guest-guide product for short-term-rental hosts: generate a preview from a listing, unlock the full guide through Stripe, then deliver a six-language guest experience.

The experiment includes queues, email delivery, a paywall, scraping/fallback paths, and explicit unit economics — the current build models a **$29 one-time product** with preview generation around **$0.04**.

**Constraint being tested:** can a narrow workflow become a self-serve, low-cost paid product?

`Cloudflare Workers` `Queues` `R2` `Stripe` `Resend` `Claude`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧾 Taxer

<sub>VERTICAL AI · TAIWAN TAX · PRIVATE BUILD</sub>

A Taiwan income-tax product that turns filing timelines, deductions, rules, calculators, and AI guidance into a guided decision flow instead of another wall of tax content.

It also experiments with AI-agent tools and AI-discovery surfaces alongside conventional SEO.

**Constraint being tested:** can a high-anxiety annual task become a clear, trustworthy guided product?

`Next.js` `AI Agent` `Tax Rules` `SEO / GEO`

</td>
<td width="50%" valign="top">

### 🔁 [Ralph for Codex](https://github.com/mason131928/codex-ralph-wiggum)

<sub>DEVTOOLS · AGENT RUNTIME · OPEN SOURCE</sub>

A recoverable loop controller for Codex that turns “keep working until the condition is actually satisfied” into an explicit state machine with persisted history, status, cancel, resume, watch, dashboard, and campaign operations.

**Constraint being tested:** how do you make long-running agent work observable and recoverable instead of magical?

`Codex` `State Machine` `Shell` `Observability`

**[View source →](https://github.com/mason131928/codex-ralph-wiggum)**

</td>
</tr>
</table>

---

## 04 / Product + engineering range

I don't try to be the deepest specialist in every layer. I try to understand enough of each layer to make **better product tradeoffs** and move a 0→1 build forward without hand-waving the hard parts.

| Layer | What I work with |
|---|---|
| **Product** | Problem discovery · PRD · UX · scope · pricing · GTM · experiments · instrumentation |
| **AI systems** | Agents · tool use · evals · RAG · realtime · multimodal · MCP · local inference |
| **Application** | TypeScript · React · Next.js · Node.js · Hono · Python |
| **Edge / cloud** | Cloudflare Workers · D1 · R2 · KV · Durable Objects · Queues · AWS · Docker |
| **Data** | PostgreSQL · SQLite · Redis · pgvector · Qdrant |
| **Local / device** | WebGPU · WebLLM · Transformers.js · BLE · firmware prototypes |
| **Operating concerns** | Cost · latency · reliability · privacy · safety · release gates · observability |

---

## 05 / Things I believe about building

`PROBLEM > MODEL`  
Start with the user friction. AI earns its place when it changes what the product can do.

`UNIT ECONOMICS ARE ARCHITECTURE`  
Latency, inference cost, queueing, storage, and support cost shape the product before they become finance problems.

`FAILURE MODES ARE PRODUCT DESIGN`  
Fallbacks, recovery, privacy boundaries, safety limits, and observability belong in the experience — not in a post-launch checklist.

`SHIP SMALL · INSTRUMENT EARLY`  
A working wedge with real signals teaches more than a large speculative roadmap.

`WORKING SOFTWARE CREATES BETTER STRATEGY`  
The fastest way to improve an idea is often to make it touch reality.

---

## 06 / Open source worth clicking

<div align="center">

<a href="https://github.com/mason131928/hashagent"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mason131928&repo=hashagent&hide_border=true&theme=transparent" width="31%" alt="HashAgent" /></a>
<a href="https://github.com/mason131928/SAGE"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mason131928&repo=SAGE&hide_border=true&theme=transparent" width="31%" alt="SAGE" /></a>
<a href="https://github.com/mason131928/codex-ralph-wiggum"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mason131928&repo=codex-ralph-wiggum&hide_border=true&theme=transparent" width="31%" alt="Ralph for Codex" /></a>

<br /><br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=mason131928&theme=github-compact&hide_border=true&area=true" />
  <img width="94%" src="https://github-readme-activity-graph.vercel.app/graph?username=mason131928&bg_color=ffffff&color=24292f&line=1f6feb&point=57606a&area=true&hide_border=true" alt="Contribution activity graph" />
</picture>

</div>

---

<div align="center">

### Build the wedge. Ship the system. Learn from reality.

**Mason Hsu · Product Builder · AI-native systems · Taipei, Taiwan 🇹🇼**

<a href="https://github.com/mason131928">GitHub</a> · <a href="https://hashagent.pages.dev">HashAgent</a> · <a href="https://imyuelao.com">月老值班中</a>

</div>