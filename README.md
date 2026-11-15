<div align="center">

# Yo, Welcome!

## Cosmin B. Memetea
### Technical Project Lead · Software Engineer · Building with AI



[![LinkedIn](https://img.shields.io/badge/LinkedIn-Cosmin--Bogdan_Memetea-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cosmin-bogdan-memetea-6450a7bb/)
[![X](https://img.shields.io/badge/X-@CosminBMemetea-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/CosminBMemetea)
![Role](https://img.shields.io/badge/Role-Technical_Project_Lead-263238?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-AI_%C2%B7_Edge_%C2%B7_Automation-6A1B9A?style=flat-square)

</div>

---

## 👋 What I'm doing

Stuff around automotive R&D, software delivery and multi-sensor systems.

I still like being close to the technology.

This account is where I build, break and test things around:

- 🤖 Agentic AI and tool-based workflows
- 🧠 RAG, evaluation and guardrails
- 🛰️ Edge AI and ROS 2
- 📡 real-time sensor pipelines
- 📦 Dockerized software and AI services
- ⚙️ engineering automation

The question I keep coming back to is simple:

> **What can technology remove, simplify or improve — and is the added complexity actually worth it?**

---

## 🧪 What I'm building


### 📊 [Project Control Tower](https://github.com/CosminBMemetea/project-control-tower)

**Portfolio governance and reporting across a shared set of goal tracks**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-SQLite-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-Installer-0078D6?style=flat-square&logo=windows&logoColor=white)
![Offline](https://img.shields.io/badge/Runs-Fully_Offline-2E7D32?style=flat-square)
![SignPath](https://img.shields.io/badge/Code_signing-SignPath-455A64?style=flat-square)

Tracks multiple projects on environment setup, planning, meeting cadence, reporting, risk and delivery health:

- Portfolio Overview — goal coverage, RAG status, open risks and a Project Health radar
- Risk Register — impact, probability, mitigation and a high-severity rollup
- Project Health — Scope / Schedule / Cost / Risk / Quality / Resources, scored 1–5
- Meeting Map, dated reports from a customizable template, and executive Approvals

The Windows app runs fully offline, installs **Only for me** with no administrator rights, and is [code-signed](https://github.com/CosminBMemetea/project-control-tower/blob/main/CODE_SIGNING.md) for free through SignPath.io (certificate by SignPath Foundation).

[Latest release →](https://github.com/CosminBMemetea/project-control-tower/releases/latest)

<div align="center">
  <img src="https://raw.githubusercontent.com/CosminBMemetea/project-control-tower/main/docs/media/pct-demo.gif" width="85%" alt="Project Control Tower — walkthrough of Portfolio Overview, Projects, Approvals, Report Template and Settings">
</div>

---

### 📡 [MultiSens](https://github.com/CosminBMemetea/multisens)

**Open-source multi-sensor platform: ingest, sync, diagnose, evaluate**

![ROS2](https://img.shields.io/badge/ROS_2-Humble-22314E?style=flat-square&logo=ros&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Release](https://img.shields.io/badge/release-v1.1.0-blue?style=flat-square)
![Tests](https://img.shields.io/badge/backend_tests-1084_passing-brightgreen?style=flat-square)

Vendor-neutral platform for anything that speaks RTSP — from ingestion and cross-sensor sync through live inference overlays.

One rule enforced end to end:

> **Every number shown is a real measurement or an explicit `N/A` — never a made-up one.**

<div align="center">
  <img src="https://raw.githubusercontent.com/CosminBMemetea/multisens/main/docs/images/multimodel_overlay_dashboard.png" width="85%" alt="MultiSens live dashboard with multi-model detection overlay">
</div>

---

### 🛰️ [ros2-x-container](https://github.com/CosminBMemetea/ros2-x-container)

**Dockerized ROS 2 vision stack for edge AI**

![ROS2](https://img.shields.io/badge/ROS_2-Humble-22314E?style=flat-square&logo=ros&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-v3%2FTiny-111111?style=flat-square)
![Foxglove](https://img.shields.io/badge/Foxglove-Studio-7C4DFF?style=flat-square)

MJPEG in, ROS 2 topics out: publishes `/image_raw` and `/annotated_image`, exposes a Foxglove WebSocket, and can run YOLOv3/Tiny detection from environment variables.

Built as a reusable playground for perception pipelines, optimized for arm64 — Mac M2 or NVIDIA Jetson.

<div align="center">
  <img src="https://github.com/user-attachments/assets/c42fc63f-7b3a-463d-a1cb-5170c4da1a7e" width="85%" alt="ROS 2-X Container — camera, detection and Foxglove overview">
</div>

---

### 🧠 [keraforge](https://github.com/CosminBMemetea/keraforge)

**Local RAG + bounded agent that abstains and cites**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-Vector_DB-DC244C?style=flat-square)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-RAG-4B32C3?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-000000?style=flat-square)

A local, observable RAG stack: Qdrant retrieval, LlamaIndex, a small Ollama model and a FastAPI query API.

If retrieval is weak, it abstains and asks a clarifying question instead of inventing an answer. Answers carry citations, and runs are traced.

<div align="center">
  <img src="https://raw.githubusercontent.com/CosminBMemetea/keraforge/main/demo-v0.1.0p0.png" width="85%" alt="keraforge local RAG demo">
</div>

---

### 🚗 [canml](https://github.com/CosminBMemetea/canml)

**CAN bus logs → pandas DataFrames**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyPI](https://img.shields.io/pypi/v/canml.svg?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-DataFrames-150458?style=flat-square&logo=pandas&logoColor=white)

Python toolkit that decodes CAN BLF logs with DBC definitions, streams large files in chunks or loads them in one call, and exports to CSV or Parquet — with signal-level filtering and DBC merging.

```bash
pip install canml
```

Also on [PyPI](https://pypi.org/project/canml/).

---

## 🌐 Live demos

<table>
<tr>
<td width="50%" valign="top">

### 🌍 [story](https://github.com/CosminBMemetea/story)

**Geotagged photos → 3D globe and a video recap**

![Next.js](https://img.shields.io/badge/Next.js-15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![three.js](https://img.shields.io/badge/three.js-Globe-049EF4?style=flat-square)
![Remotion](https://img.shields.io/badge/Remotion-Video-000000?style=flat-square)
[![Live demo](https://img.shields.io/badge/▶_Live_demo-2E7D32?style=flat-square)](https://cosminbmemetea.github.io/story/)

Drop travel photos in the browser; GPS is read on-device and mapped onto an interactive globe, with a short Remotion recap. Photos never leave your device.

</td>
<td width="50%" valign="top">

### 🚛 [igo](https://github.com/CosminBMemetea/igo)

**Profit per trip and fuel savings for trucks and farm machinery**

![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![i18n](https://img.shields.io/badge/i18n-RO_%2F_EN_%2F_PL-546E7A?style=flat-square)
[![Live demo](https://img.shields.io/badge/▶_Live_demo-2E7D32?style=flat-square)](https://igo-kappa.vercel.app)

The two numbers up front: fuel saved versus baseline, and profit per trip (revenue − diesel − tolls − driver − other). Public demo uses fictional, labelled data.

</td>
</tr>
</table>

---

## 🎮 Just for fun

<table>
<tr>
<td width="50%" valign="top">

### 🐤 [zdappy-bird](https://github.com/CosminBMemetea/zdappy-bird)

**Flappy Bird in the browser, with an ERC-721 bird contract**

![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-ERC--721-363636?style=flat-square&logo=solidity&logoColor=white)
[![Live demo](https://img.shields.io/badge/▶_Play-00C853?style=flat-square)](https://cosminbmemetea.github.io/zdappy-bird/)

Click, tap or press Space to flap. No wallet is required to play; connecting one is optional and testnet-only. The ERC-721 contract lives in the repo and is not deployed.

</td>
<td width="50%" valign="top">

### 🛡️ [yoda-level-github-badge](https://github.com/CosminBMemetea/yoda-level-github-badge)

**Star Wars–themed rank badges for a GitHub profile README**

![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![SVG](https://img.shields.io/badge/SVG-Badges-FFB300?style=flat-square)
[![Live demo](https://img.shields.io/badge/▶_Badge_Studio-6A1B9A?style=flat-square)](https://yoda-level-github-badge.vercel.app/ui)

Tiers from Force Beginner to Master Yoda, XP bars, streaks, achievement trials and head-to-head duels — all as plain SVG.

</td>
</tr>
</table>

---

## 🏢 Client projects

- 🚚 [Querra Fleet](https://fleet.querra.net)
- 📄 [Querra Docs](https://qerradoc.vercel.app)

---

<details>
<summary><b>🔧 Smaller tools and experiments</b></summary>
<br>

- 📹 [multirtsp](https://github.com/CosminBMemetea/multirtsp) — one camera → synchronized RGB, pseudo-depth and pseudo-thermal RTSP streams (FFmpeg + MediaMTX)
- 🗺️ [scrum-guide-mindmap](https://github.com/CosminBMemetea/scrum-guide-mindmap) — a mind map for every topic in the Scrum Guide 2020

</details>

## 🤝 How I use AI to build

I use AI heavily.

Not just for autocomplete.

I use **ChatGPT, Claude, Gemini and Grok** as different agents for things like:

- exploring designs
- breaking requirements down
- writing code
- reviewing code
- finding edge cases
- challenging architectural decisions
- generating tests
- debugging
- documentation

And yes:

**I don't manually inspect every line produced by an AI agent.**

For some tasks I use another agent to review the implementation, then tests, runtime behaviour and targeted inspection to decide whether I trust the result.

I like automation.

If something repetitive can be removed from my work, I usually want to remove it.

But there is one boundary I don't outsource:

> **The responsibility for what I ship is still mine.**

AI can propose, generate, review and challenge.

It cannot own the consequence.

---

## 🧰 Toolbox

<details open>
<summary><b>💻 Programming</b></summary>
<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-333333?style=flat-square&logo=javascript&logoColor=F7DF1E)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white)

</details>

<details>
<summary><b>🧠 AI / Data</b></summary>
<br>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-Vector_DB-DC244C?style=flat-square)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-RAG-4B32C3?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-000000?style=flat-square)
![Sentence Transformers](https://img.shields.io/badge/Sentence_Transformers-Embeddings-F9A825?style=flat-square)
![DVC](https://img.shields.io/badge/DVC-945DD6?style=flat-square&logo=dvc&logoColor=white)

</details>

<details>
<summary><b>🛰️ Edge / Systems</b></summary>
<br>

![ROS2](https://img.shields.io/badge/ROS_2-Humble-22314E?style=flat-square&logo=ros&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

</details>

<details>
<summary><b>🔧 Software Engineering</b></summary>
<br>

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-Unit_Testing-239120?style=flat-square)
![OSGi](https://img.shields.io/badge/OSGi-Modular_Java-5A5A5A?style=flat-square)

</details>

<details>
<summary><b>📋 Project & Delivery</b></summary>
<br>

![Technical Leadership](https://img.shields.io/badge/Technical-Project_Leadership-263238?style=flat-square)
![Scrum](https://img.shields.io/badge/Scrum-Agile_Delivery-009FDA?style=flat-square)
![PSM I](https://img.shields.io/badge/Scrum.org-PSM_I-009FDA?style=flat-square)
![Project Management](https://img.shields.io/badge/Project-Management-455A64?style=flat-square)
![Risk Management](https://img.shields.io/badge/Risk-Management-6D4C41?style=flat-square)
![Stakeholders](https://img.shields.io/badge/Stakeholder-Alignment-546E7A?style=flat-square)
![Release Management](https://img.shields.io/badge/Release-Management-3949AB?style=flat-square)
![Cross Functional](https://img.shields.io/badge/Cross--Functional-Coordination-00897B?style=flat-square)

</details>

<details>
<summary><b>🤖 AI tools in my workflow</b></summary>
<br>

![ChatGPT](https://img.shields.io/badge/ChatGPT-10A37F?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![Grok](https://img.shields.io/badge/Grok-000000?style=flat-square&logo=x&logoColor=white)

</details>

---

## 🧭 Where I'm heading

I want to stay in the space between **technology and delivery**.

Not detached from engineering.

Not pretending to be the best ML researcher in the room.

I want to understand enough of the system to ask the right questions, challenge technical decisions, structure the work, and make sure what gets built creates value.

The areas pulling me most right now are:

**Technical Project Leadership · AI Platforms · Agentic Systems · Engineering Automation**

---

<div align="center">

![Yoda Trials](https://yoda-level-github-badge.vercel.app/api/trials?username=CosminBMemetea&detailed=1&cols=3&theme=sith)

### ⚙️ Automate what should be automated.  
### 🧠 Understand what matters.  
### 👤 Own the result.

[![Views](https://komarev.com/ghpvc/?username=CosminBMemetea&color=brightgreen&style=flat-square)]()

</div>
