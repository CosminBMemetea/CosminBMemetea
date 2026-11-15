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

### 🧠 [keraforge](https://github.com/CosminBMemetea/keraforge)

**RAG + bounded-agent playground**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-Vector_DB-DC244C?style=flat-square)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-RAG-4B32C3?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-000000?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

My experiment in building AI workflows that are observable instead of magical.

Current work includes:

- semantic retrieval
- RAG
- retrieval quality checks
- abstention when context is weak
- citations / provenance
- workflow tracing
- evaluation
- bounded tool use
- constrained agent execution

The agent is intentionally limited.

I am more interested in **controllable systems that fail visibly** than agents that appear autonomous until something goes wrong.

---

### 🛰️ [ros2-x-container](https://github.com/CosminBMemetea/ros2-x-container)

**Dockerized ROS 2 vision environment**

![ROS2](https://img.shields.io/badge/ROS_2-Humble-22314E?style=flat-square&logo=ros&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

Reusable playground for:

- camera → ROS 2 topics
- image processing
- YOLO experiments
- Foxglove visualization
- Dockerized execution
- NVIDIA Jetson trials

I use it to experiment with the plumbing around perception systems, not only the model itself.

---

### 📡 [multirtsp](https://github.com/CosminBMemetea/multirtsp)

**One capture → multiple synchronized RTSP streams**

![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![RTSP](https://img.shields.io/badge/RTSP-Streaming-455A64?style=flat-square)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white)

A small utility for developing multi-stream perception pipelines when the full sensor setup is not available.

Current setup produces:

- RGB
- pseudo-depth
- pseudo-thermal

from one source using FFmpeg and MediaMTX.

---

### 🤖 [model-mesh](https://github.com/CosminBMemetea/model-mesh)

**Small ML serving experiment**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-945DD6?style=flat-square&logo=dvc&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-S3-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Experimenting with:

- model adapters
- inference APIs
- model/data separation
- DVC
- artifact storage
- Dockerized deployment

---

### 📹 [webcam2rtsp](https://github.com/CosminBMemetea/webcam2rtsp)

**Webcam → H.264 RTSP**

![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![H264](https://img.shields.io/badge/H.264-Streaming-455A64?style=flat-square)

A small utility because sometimes the useful thing is simply making two systems talk to each other.

---

### 📊 [dashboards](https://github.com/CosminBMemetea/dashboards)

**Engineering delivery analytics**

![Analytics](https://img.shields.io/badge/Engineering-Analytics-1565C0?style=flat-square)
![Agile](https://img.shields.io/badge/Agile-Delivery-00897B?style=flat-square)

Experiments around sprint data, burndowns and lightweight reporting.

---

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
