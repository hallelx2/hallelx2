<div align="center">

<img src="https://avatars.githubusercontent.com/u/98324073?v=4" width="120" style="border-radius:50%" alt="Halleluyah" />

# Halleluyah — `@hallelx2`

**AI engineer. Builder from Nigeria.**

I build production agentic systems with tool use, retrieval, and event-sourced state — across Claude Agent SDK, Vercel AI SDK, OpenAI tools, and VAPI. Three shipped in 2026 — Video Studio, AuraHealth, NotebookLM-clone — and the open-source retrieval substrate underneath them.

[![Vectorless](https://img.shields.io/badge/Launching-vectorless.store-black?style=flat-square)](https://vectorless.store)
[![Location](https://img.shields.io/badge/📍-Nigeria-008751?style=flat-square)]()
[![Open to work](https://img.shields.io/badge/Open%20to-Contracts%20%7C%20AI%20Engineering%20%7C%20Research-brightgreen?style=flat-square)]()
[![Followers](https://img.shields.io/github/followers/hallelx2?style=flat-square&label=Follow&color=blue)](https://github.com/hallelx2)

</div>

---

### About

I build agentic systems that do real work in production. Tool use, retrieval, approval gates, real users — across whichever runtime the product needs (Claude Agent SDK, Vercel AI SDK, OpenAI tools, VAPI, MCP). Underneath sits the retrieval layer I open-source as **Vectorless** — structure-preserving document retrieval, no chunking, no top-K, no vector DB.

Most of what I finish starts as a friction point I have personally watched break down — hospital payment queues, document retrieval, agent memory across sessions — and ends as a product someone else can use today. I am also a medical student, which is why a lot of the harder problems on this page live somewhere near a hospital.

**Available for contract work** in agentic systems, RAG / retrieval engineering, and applied healthcare AI.

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
| **[llmgate](https://github.com/hallelx2/llmgate)** | LiteLLM for Go — provider-agnostic LLM client over Anthropic, OpenAI, Gemini with router, fallback, cost tracking, capability flags, composable middleware. |

---

### 🧠 Agentic Systems (production builds)

Big internal builds — included so you know the scope.

- **Video Studio** — Agent-driven launch-video generator: reads a README, drafts script, narrates with Kokoro TTS, composes HTML+GSAP scenes, renders MP4. Electron + Claude Agent SDK + HyperFrames.
- **Flowstate** — Markdown-driven agent automation system. Define agents as plain `.md` files; bind them to your already-authenticated CLIs, MCP servers, and skills as tools. Spatial flow view of every step.
- **NotebookLM Clone** — Self-hosted, local-first NotebookLM with three-stage retrieval (query expansion → hybrid pgvector + keyword → LLM rerank), self-critiquing deep-research agent, and two-host audio overviews. Next.js 15 + AI SDK v6 + pgvector.
- **Hercules** — Desktop research agent for systematic reviews and meta-analyses. Tauri 2 + Claude Agent SDK + multi-algorithm orchestration.
- **Enterprise AI consulting engagement** _(anonymized)_ — AI call-answering system, SMS command center, and dashboard chatbot for a service-business vertical. LangGraph state machines, Twilio voice/SMS, multi-tenant DB tooling.

---

### 🏥 Healthcare & Medical AI

Where my medical training shows up in the code.

- **AuraHealth · Hallex Medical · Helix AI · Voxtar** — see *Live Products* above.
- **[Breast-Cancer](https://github.com/hallelx2/Breast-Cancer)** — analyzing public datasets to investigate breast cancer pathogenesis.
- **[breast-cancer-detection](https://github.com/hallelx2/breast-cancer-detection)** — Streamlit classifier with radar-chart explanations + full metrics dashboard.
- **[cancerag](https://github.com/hallelx2/cancerag)** — In-silico exploration of biased agonists for high-yield cancer pathways.
- **[coronavirus-drug-discovery](https://github.com/hallelx2/coronavirus-drug-discovery)** — ChEMBL exploration for COVID drug targets.
- **child-immunization-tracking-system** — immunization workflow tooling.

---

### 🔬 Research & ML

- **[arxhimedes](https://github.com/hallelx2/arxhimedes)** — SynthesisAI: PubMed research synthesis via LLMs + knowledge graphs with Graph-RAG.
- **swarmtorch** — see *Open-Source* above. Paper in progress on metaheuristic-vs-gradient training and HPO.
- **Skill-Based Test** — Research comparing skills-based personalization vs LoRA fine-tuning for AI personas.
- **gonforcement-learning** — Terminal-native RL playground in pure Go: Q-learning, DQN, PPO with live Bubble Tea TUI.

---

### ⛓️ Web3 — adjacent work

A decentralized marketplace for renting game assets on Solana. Four repos, full stack — kept here for completeness.

- **[scrunchy-contract](https://github.com/hallelx2/scrunchy-contract)** — Solana Anchor programs.
- **[scrunchy-backend](https://github.com/hallelx2/scrunchy-backend)** — NestJS: wallet auth, on-chain integration, rentals.
- **[scrunchy-cli](https://github.com/hallelx2/scrunchy-cli)** — Python CLI that scaffolds Scrunchy into Unity/game projects.
- **[scrunchy-frontend](https://github.com/hallelx2/scrunchy-frontend)** — Next.js marketplace UI.
- Adjacent: **[phantomzero-vrf](https://github.com/hallelx2/phantomzero-vrf)**, **[hallelx2-bank](https://github.com/hallelx2/hallelx2-bank)**, **chainvote**.

---

### 🧰 Stack

**Languages** TypeScript · Python · Rust · Go · R
**Agent runtimes** Claude Agent SDK · Vercel AI SDK · OpenAI tools · VAPI · MCP · LangGraph
**LLMs** Claude Opus/Sonnet/Haiku · Gemini 2.5 Pro/Flash · GPT-4o · YarnGPT
**Retrieval / data** Vectorless · pgvector · Qdrant · Actian VectorAI DB · Graph-RAG
**Voice** Deepgram · ElevenLabs · Kokoro · YarnGPT · Twilio · VAPI
**Web** Next.js 15 · Fastify · NestJS · Hono · FastAPI · Gradio
**Desktop** Electron · Tauri 2 · Remotion · HyperFrames
**Web3** Solana · Anchor · VRF
**Infra** Neon · Drizzle · Supabase · Cloudflare Workers · QStash · R2 · Docker · Vercel · n8n

---

### 📫 Find me

- 🌍 **Portfolio:** [portfolio.hallelx2.com](https://portfolio.hallelx2.com)
- 🚀 **Current focus:** [vectorless.store](https://vectorless.store)
- 🐙 **GitHub:** [@hallelx2](https://github.com/hallelx2)
- 💼 **Open to:** Contracts, AI engineering roles, research collaborations

<div align="center">

<sub>⚡ Building at the edge of medicine, machines, and trust.</sub>

</div>
