<div align="center">

<img src="https://avatars.githubusercontent.com/u/98324073?v=4" width="120" style="border-radius:50%" alt="Halleluyah" />

# Halleluyah — `@hallelx2`

**Medical student. AI engineer. Builder from Nigeria.**
I ship retrieval systems, agentic voice products, and Web3 infrastructure —
often aimed at problems I've watched go unsolved in African healthcare and fintech.

[![Vectorless](https://img.shields.io/badge/Launching-vectorless.store-black?style=flat-square)](https://vectorless.store)
[![Location](https://img.shields.io/badge/📍-Nigeria-008751?style=flat-square)]()
[![Open to work](https://img.shields.io/badge/Open%20to-AI%20Engineering%20%7C%20Research%20%7C%20Hackathons-brightgreen?style=flat-square)]()
[![Followers](https://img.shields.io/github/followers/hallelx2?style=flat-square&label=Follow&color=blue)](https://github.com/hallelx2)

</div>

---

### About

I build at the intersection of **AI, medicine, and decentralized systems**. Medical school taught me to read pathology; a decade of tinkering taught me to ship. The two meet in the work I do: retrieval systems that reason instead of chunk, voice-first agents that triage real patients, and on-chain primitives for things that need to be trustless.

Most projects I finish share a pattern — they solve a friction point I've personally watched break down (hospital payment queues, research synthesis over PubMed, agent memory across sessions).

---

### 🛠️ Shipped & Packaged

Things that exist as real packages, live URLs, or CI-backed releases.

| Project | What it does |
|---|---|
| **[vectorless](https://github.com/hallelx2/vectorless)** → [vectorless.store](https://vectorless.store) | Document retrieval for the reasoning era — structure-preserving retrieval where LLMs navigate a document's table of contents instead of vector-similarity chunks. TS + Python SDKs on npm + PyPI, Next.js + Fastify backend. |
| **[context8](https://github.com/hallelx2/context8)** | Collective problem-solving memory for coding agents. Every time an agent solves an uncommon error, Context8 stores the fix so any agent can retrieve it later via MCP. Powered by Actian VectorAI DB. _(PyPI)_ |
| **[tytube](https://github.com/hallelx2/tytube)** | TypeScript port of `pytube` — YouTube metadata, streams, captions, playlists, channels, search. No API key. Node, Bun, browser. _(npm, signed provenance)_ |
| **[youtube-transcript-ts](https://github.com/hallelx2/youtube-transcript-ts)** | TypeScript port of `youtube-transcript-api`. Transcripts, translation, multi-format output. _(npm)_ |
| **[yarngpt-sdk](https://github.com/hallelx2/yarngpt-sdk)** | Unofficial Python SDK for YarnGPT — Nigerian-accent TTS across 16 voices, async + CLI. _(PyPI)_ |
| **[bridgehook](https://github.com/hallelx2/bridgehook)** | Zero-install ngrok alternative. Forwards webhooks to localhost using the browser as the proxy (SSE + fetch over a Cloudflare Worker relay). |

---

### 🏥 Agentic Voice for Healthcare & Lifestyle

An ongoing bet: the fastest way to fix African healthcare friction is a **voice agent in the patient's language**, wired to payments and clinical workflows.

- **[AuraHealth](https://github.com/hallelx2/aurahealth)** / **[enyata-project](https://github.com/hallelx2/enyata-project)** — Voice triage + Interswitch escrow to kill Nigerian hospital payment queues. VAPI + Deepgram + ElevenLabs + Gemini 2.5 Pro routing. _[Live](https://aurahealth-five.vercel.app)_
- **[hallex-medical](https://github.com/hallelx2/hallex-medical)** — Clinician-side dashboard: VAPI intake, Gemini for ICD-10 coding & differentials, RAG "chat with the case." Next.js 15, Neon, Drizzle, Clerk. _[Live](https://st-mary-hospital-theta.vercel.app)_
- **[aurasense](https://github.com/hallelx2/aurasense-backend)** — Voice-first agentic companion spanning commerce, travel, and social, with voice biometrics and a temporal knowledge graph.
- **[legal-ai](https://github.com/hallelx2/legal-ai)** — Drafting, managing, and e-signing legal agreements with AI.
- **[pdf-to-audio](https://github.com/hallelx2/pdf-to-audio)** — Mastra workflow: PDF → summary → listenable audio.

---

### ⛓️ Web3 — The Scrunchy Stack

A decentralized marketplace for renting game assets on Solana. Four repos, full stack.

- **[scrunchy-contract](https://github.com/hallelx2/scrunchy-contract)** — Solana Anchor programs: asset-registry, marketplace, access-control.
- **[scrunchy-backend](https://github.com/hallelx2/scrunchy-backend)** — NestJS: wallet auth, on-chain integration, rentals, API keys with rate limiting, Redis, cron.
- **[scrunchy-cli](https://github.com/hallelx2/scrunchy-cli)** — Python CLI that scaffolds Scrunchy components into Unity/game projects with wallet auth.
- **[scrunchy-frontend](https://github.com/hallelx2/scrunchy-frontend)** — Next.js marketplace UI.

Adjacent: **[phantomzero-vrf](https://github.com/hallelx2/phantomzero-vrf)** (Solana VRF-based betting), **[hallelx2-bank](https://github.com/hallelx2/hallelx2-bank)** (programmable credit cards).

---

### 🔬 Research & ML

- **[swarmtorch](https://github.com/hallelx2/swarmtorch)** — PyTorch library of **120 metaheuristic optimization algorithms** (60 training optimizers + 60 HPO searchers). GPU-accelerated, PyTorch-native API, paper in progress. ⭐
- **[arxhimedes](https://github.com/hallelx2/arxhimedes)** — SynthesisAI: research synthesis over PubMed combining LLMs + knowledge graphs with Graph-RAG and multi-tier chunking (Dgraph).
- **[breast-cancer-detection](https://github.com/hallelx2/breast-cancer-detection)** — Wisconsin-dataset classifier with radar-chart explanations and a full model-metrics dashboard.
- **[cancerag](https://github.com/hallelx2/cancerag)** — In-silico exploration of biased agonists for high-yield cancer pathways.
- **[finance-gpt](https://github.com/hallelx2/finance-gpt)** — Daily Scrapy scrape → Bedrock embeddings → MongoDB Atlas vector store → LangChain + OpenAI. Financial RAG.

---

### 🧰 Stack

**Languages** TypeScript · Python · Rust · Go · R
**AI/ML** PyTorch · LangChain · MCP · Gemini 2.5 Pro · Claude · Actian VectorAI DB · Graph-RAG
**Voice** VAPI · Deepgram · ElevenLabs · YarnGPT
**Web** Next.js 15 · Fastify · NestJS · Hono · Tauri 2
**Web3** Solana · Anchor · VRF
**Infra** Neon · Drizzle · Cloudflare Workers · QStash · R2 · Docker · Vercel

---

### 📫 Find me

- 🌍 **Current focus:** [vectorless.store](https://vectorless.store)
- 🐙 **GitHub:** [@hallelx2](https://github.com/hallelx2)
- 💼 **Open to:** AI engineering roles, research collaborations, and hackathon teams

<div align="center">

<sub>⚡ Building at the edge of medicine, machines, and trust.</sub>

</div>
