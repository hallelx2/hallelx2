<div align="center">

<img src="https://avatars.githubusercontent.com/u/98324073?v=4" width="120" style="border-radius:50%" alt="Halleluyah" />

# Halleluyah — `@hallelx2`

**Medical student. AI engineer. Builder from Nigeria.**

I ship SaaS products, retrieval systems, agentic voice products, and Web3 infrastructure —
often aimed at problems I've watched go unsolved in African healthcare and global developer tooling.

[![Vectorless](https://img.shields.io/badge/Launching-vectorless.store-black?style=flat-square)](https://vectorless.store)
[![Location](https://img.shields.io/badge/📍-Nigeria-008751?style=flat-square)]()
[![Open to work](https://img.shields.io/badge/Open%20to-AI%20Engineering%20%7C%20Research%20%7C%20Hackathons-brightgreen?style=flat-square)]()
[![Followers](https://img.shields.io/github/followers/hallelx2?style=flat-square&label=Follow&color=blue)](https://github.com/hallelx2)

</div>

---

### About

I build at the intersection of **AI, medicine, and decentralized systems**. Medical school taught me to read pathology; a decade of tinkering taught me to ship. The two meet in the work I do: retrieval systems that reason instead of chunk, voice-first agents that triage real patients, desktop research tools for systematic reviews, and on-chain primitives for things that need to be trustless.

Most of what I finish starts as a friction point I've personally watched break down — hospital payment queues, PubMed synthesis, agent memory across sessions — and ends as a product someone else can use today.

---

### 🚀 Live Products

| Product | What it does | Link |
|---|---|---|
| **Vectorless** | Document retrieval for the reasoning era — LLMs navigate document maps instead of vector chunks. SDKs on npm + PyPI. | [vectorless.store](https://vectorless.store) |
| **Voxtar** | SaaS product — closed beta. | [voxtar.hallelx2.com](https://voxtar.hallelx2.com) |
| **Coursified** | SaaS learning platform — in build. | [coursified.app](https://coursified.app) |
| **Hypatia** | AI learning platform that teaches with generated analogies + Markmap/Mermaid visualizations. | [hypatia.cv](https://hypatia.cv) |
| **Helix AI** | Precision medicine application. | [helixai-taupe.vercel.app](https://helixai-taupe.vercel.app) |
| **AuraHealth** | Voice triage + Interswitch escrow for Nigerian hospital payment queues. VAPI + Gemini 2.5 Pro. | [aurahealth-five.vercel.app](https://aurahealth-five.vercel.app) |
| **Hallex Medical** | Clinician-side triage dashboard: Gemini 2.5 Pro clinical reasoning, RAG over call transcripts. | [st-mary-hospital-theta.vercel.app](https://st-mary-hospital-theta.vercel.app) |

---

### 📦 Open-Source & Packaged

Things shipped as real npm / PyPI packages with CI and live users.

| Project | What it does |
|---|---|
| **[vectorless](https://github.com/hallelx2/vectorless)** | Structure-preserving document retrieval. TS + Python SDKs on npm + PyPI. Next.js + Fastify. |
| **[context8](https://github.com/hallelx2/context8)** | Collective memory for coding agents — stores solved errors in a vector DB so agents can retrieve fixes via MCP. Built on Actian VectorAI DB. _(PyPI)_ |
| **[tytube](https://github.com/hallelx2/tytube)** | TypeScript port of `pytube`: YouTube metadata, streams, captions — no API key. Node / Bun / browser. _(npm, signed)_ |
| **[youtube-transcript-ts](https://github.com/hallelx2/youtube-transcript-ts)** | TypeScript port of `youtube-transcript-api` with translation + multi-format. _(npm)_ |
| **[yarngpt-sdk](https://github.com/hallelx2/yarngpt-sdk)** | Unofficial Python SDK for YarnGPT's Nigerian-accent TTS — 16 voices, async + CLI. _(PyPI)_ |
| **[swarmtorch](https://github.com/hallelx2/swarmtorch)** ⭐ | PyTorch library of **120 metaheuristic optimization algorithms** (60 training + 60 HPO). GPU-accelerated, drop-in `torch.optim.Optimizer`. _(PyPI, paper in progress)_ |
| **[bridgehook](https://github.com/hallelx2/bridgehook)** | Zero-install ngrok alternative — forwards webhooks to localhost via browser + Cloudflare Worker relay. |

---

### 🧠 Agentic Systems (private, production)

Big internal builds that aren't public yet — included so you know the scope.

- **Hercules** — Desktop research agent for systematic reviews & meta-analyses. Tauri 2 + Claude Agent SDK + multi-algorithm orchestration. Three interaction modes (manual / supervised / YOLO), Zotero + Mendeley integrations.
- **Video Studio** — Agent-driven launch-video generator: reads a README, renders multi-format MP4 via Remotion. Tauri 2 + Claude Agent SDK.
- **NotebookLM Clone** — Full-stack document AI with RAG, podcast generation, and voice chat. Python + Gradio + FastAPI + Qdrant.
- **Enterprise AI consulting engagement** _(anonymized)_ — Built an AI call-answering system, SMS command center, and dashboard chatbot for a service-business vertical. LangGraph state machines, Twilio voice/SMS, LLM guardrails, multi-tenant DB tooling.
- **AI Automation** — Bun/TS platform managing self-hosted n8n workflows via REST API.

---

### 🏥 Healthcare & Medical AI

Where my medical training shows up in the code.

- **AuraHealth · Hallex Medical · Helix AI** — see *Live Products* above.
- **[Breast-Cancer](https://github.com/hallelx2/Breast-Cancer)** — analyzing public datasets to investigate breast cancer pathogenesis.
- **[breast-cancer-detection](https://github.com/hallelx2/breast-cancer-detection)** — Streamlit classifier with radar-chart explanations + full metrics dashboard.
- **[cancerag](https://github.com/hallelx2/cancerag)** — In-silico exploration of biased agonists for high-yield cancer pathways.
- **[coronavirus-drug-discovery](https://github.com/hallelx2/coronavirus-drug-discovery)** — ChEMBL exploration for COVID drug targets.
- **child-immunization-tracking-system** — immunization workflow tooling.

---

### ⛓️ Web3 — The Scrunchy Stack

A decentralized marketplace for renting game assets on Solana. Four repos, full stack.

- **[scrunchy-contract](https://github.com/hallelx2/scrunchy-contract)** — Solana Anchor programs: asset-registry, marketplace, access-control.
- **[scrunchy-backend](https://github.com/hallelx2/scrunchy-backend)** — NestJS: wallet auth, on-chain integration, rentals, Redis, cron.
- **[scrunchy-cli](https://github.com/hallelx2/scrunchy-cli)** — Python CLI that scaffolds Scrunchy into Unity/game projects with wallet auth.
- **[scrunchy-frontend](https://github.com/hallelx2/scrunchy-frontend)** — Next.js marketplace UI.

Adjacent: **[phantomzero-vrf](https://github.com/hallelx2/phantomzero-vrf)** (Solana VRF betting), **[hallelx2-bank](https://github.com/hallelx2/hallelx2-bank)** (programmable cards), **chainvote** (Partisia on-chain voting).

---

### 🔬 Research & ML

- **[arxhimedes](https://github.com/hallelx2/arxhimedes)** — SynthesisAI: PubMed research synthesis via LLMs + knowledge graphs with Graph-RAG.
- **Archimedes (hackathon)** — AI-powered parametric design for robotic arms. Gemini 3 hackathon build.
- **Skill-Based Test** — Research comparing skills-based personalization vs LoRA fine-tuning for AI personas.
- **gonforcement-learning** — Terminal-native RL playground in pure Go: Q-learning, DQN, PPO with live Bubble Tea TUI.

---

### 🧰 Stack

**Languages** TypeScript · Python · Rust · Go · R
**AI/ML** PyTorch · LangGraph · LangChain · MCP · Claude Agent SDK · Gemini 2.5 Pro · Graph-RAG · Actian VectorAI DB · Qdrant
**Voice** VAPI · Deepgram · ElevenLabs · YarnGPT · Twilio
**Web** Next.js 15 · Fastify · NestJS · Hono · FastAPI · Gradio
**Desktop** Tauri 2 · Remotion
**Web3** Solana · Anchor · VRF
**Infra** Neon · Drizzle · Supabase · Cloudflare Workers · QStash · R2 · Docker · Vercel · n8n

---

### 📫 Find me

- 🌍 **Portfolio:** [portfolio.hallelx2.com](https://portfolio.hallelx2.com)
- 🚀 **Current focus:** [vectorless.store](https://vectorless.store)
- 🐙 **GitHub:** [@hallelx2](https://github.com/hallelx2)
- 💼 **Open to:** AI engineering roles, research collaborations, hackathon teams

<div align="center">

<sub>⚡ Building at the edge of medicine, machines, and trust.</sub>

</div>
