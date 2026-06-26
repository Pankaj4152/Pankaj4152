<p align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="110"/>
</p>

<h1 align="center">Hi, I'm <span>Pankaj Goyal</span> 👋</h1>
<h3 align="center">AI Engineer · Backend Developer · Builder</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/pankaj4152/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:pankajgoyal4152@gmail.com">
    <img src="https://img.shields.io/badge/Email-FF3D3D?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://leetcode.com/u/Pankaj4152/">
    <img src="https://img.shields.io/badge/LeetCode-F89F1B?style=for-the-badge&logo=leetcode&logoColor=white"/>
  </a>
  <a href="https://medium.com/@pankajgoyal4152">
    <img src="https://img.shields.io/badge/Medium-000?style=for-the-badge&logo=medium&logoColor=white"/>
  </a>
</p>

---

## 🚀 About Me

I build AI systems and backend infrastructure — mostly from scratch, to actually understand them.

My work sits at the intersection of **LLM systems, backend engineering, and real product development**. I care about resilience, memory, and making AI useful beyond a single session. Currently exploring how persistent memory can change what AI agents are capable of — for individuals and for engineering teams.

---

## 🔬 What I'm Building

---

### 🔷 KAIROS Personal — AI Assistant with Persistent Memory
> *Knowledge-driven Artificial Intelligence for Real-time Operations System*

**[GitHub →](https://github.com/Pankaj4152/KAIROS)**

A Jarvis-style personal AI assistant that runs on my own hardware. Voice at home, Telegram when out, browser UI from anywhere — all with shared persistent memory across every session.

**What makes it different:**
- **3-tier LLM routing** — local Ollama for simple tasks, cloud only when needed, automatic fallback
- **Hybrid memory architecture** — SQLite + vector search + session persistence for cross-session semantic recall
- **Async orchestration pipeline** — context retrieval, history loading, and tool execution run concurrently to minimize latency
- **Resilience-first design** — multi-tier fallback, retry/backoff, graceful degradation; the system keeps working even when models or tools fail
- **Proactive agent** — daily briefings, reminders, scheduled tasks without being asked

**Tools:** Web search (Brave/Tavily/DuckDuckGo), Google Calendar, Gmail, task management, SMTP

**Stack:** Python 3.12 · FastAPI · LiteLLM · Ollama (Qwen2.5) · Gemini · SQLite + sqlite-vec · APScheduler · Docker · Tailscale

---

### 🔷 KAIROS for Teams — Persistent Memory Layer for Engineering Teams *(Building)*

Engineering teams produce enormous amounts of knowledge every day — decisions made, bugs fixed, systems designed — but it ends up scattered across Jira, GitHub, Slack, and docs. When it's needed later, engineers spend hours hunting for it and often miss it entirely.

In the AI era, this gets worse. Coding agents like Claude Code and Cursor start completely blind every session — no memory of what your team built, what broke before, or why a decision was made.

**KAIROS for Teams fixes this.** It's a persistent memory layer for engineering teams that keeps track of everything across a project and makes it instantly queryable — whether it's a new joiner understanding the system, a senior engineer asking why a call was made 6 months ago, or an AI agent about to repeat a mistake your team already made.

It removes the friction before every decision, so your team spends less time finding context and more time actually building.

> *Early stage — actively building.*

---

### 🔷 [Scratchers](https://github.com/Pankaj4152/Scratchers) — AI Systems Built From Scratch

A learning ground where I implement core AI components without frameworks, to actually understand them.

**Built so far:**
- **Neural network in NumPy** — forward/back propagation, gradient descent, trained on MNIST
- **Modular RAG pipeline** — 6 stages: ingestion → cleaning → chunking → embedding → retrieval → generation
- **Custom vector store** — cosine similarity search with persistent embedding + metadata storage
- **Benchmarking framework** — evaluates chunking strategies, retrievers, embedding models, and LLMs on retrieval and answer-quality metrics

---

### 🔷 [Smart Photo Finder](https://github.com/Pankaj4152/smart-photo-finder) — Semantic Image Search, 100% Offline ⭐ 12

Find images by describing what you're looking for — not by filename or tags.

Built for the **NexaAI Builder Bounty Program**.

- **Vision-language model** (NexaAI Qwen3-VL-4B) generates natural language descriptions of every image
- **384D semantic embeddings** (all-MiniLM-L6-v2) convert descriptions to vectors
- **Cosine similarity search** returns ranked results in <100ms for 1000 images
- 100% offline, zero cloud APIs, zero cost — privacy-first by design
- Modular architecture: services for VLM, embedding, processing; separate search engine and JSON-based local DB

**Stack:** Python · NexaAI SDK · Sentence-Transformers · Cosine Similarity

**Demo:** [YouTube](https://youtu.be/YVkPa-aJpEo)

---

### 🔷 [Issuenix](https://issuenix.com) — Certificate Issuance & Verification Platform *(Live)*

Full-stack SaaS for organizations to issue and verify tamper-proof digital certificates.

- Hash-based document verification prevents forgery
- Async bulk certificate generation via CSV + automated SMTP delivery pipelines
- AI assistant **Sonia** (Gemini + RAG) for workflow automation
- FastAPI backend · PostgreSQL · React frontend · Docker · JWT/RBAC

---

### 🔷 AI Insight Pro — Data Intelligence Platform *(@ AIPlaneTech, Jun–Jul 2025)*

**[GitHub →](https://github.com/Pankaj4152/AI-Insight-Pro)**

Contributed to a data platform supporting 7+ data sources (PostgreSQL, BigQuery, cloud storage, PDFs, CSVs, JSON, text).

- Backend services for data scanning, metadata extraction, and risk assessment
- Semantic matching + rule-based detection for PII and Sensitive Data Elements
- PostgreSQL-backed persistence for compliance reporting and audit trails
- Multi-agent LLM workflows (Gemini) + RAG pipeline for policy/report querying

---

## 🧠 Skills

| Category | Stack |
|---|---|
| **Languages** | Python · C++ · SQL |
| **AI / ML** | LLMs · RAG · Embeddings · Vector DBs · Semantic Search · NLP · Neural Networks · Prompt Engineering |
| **Frameworks** | FastAPI · PyTorch · NumPy · HuggingFace Transformers |
| **Backend** | REST APIs · Async Programming · Model Serving · Auth/RBAC · Caching |
| **Databases** | PostgreSQL · SQLite · MongoDB · ChromaDB · VectorDB |
| **Tools & Infra** | Git · Docker · Linux · Ollama · LiteLLM · GCP · AWS |
| **CS Core** | DSA · OOP · DBMS · Operating Systems · Computer Networks |

---

## 🏆 A Few Other Things

- 🥇 **Ranked 29th nationally** — IIT Bombay National Entrepreneurship Challenge (NEC) 2025
- 💻 **300+ DSA problems** solved on LeetCode and other platforms
- ✍️ Write about ML, neural networks, and AI systems on [Medium](https://medium.com/@pankajgoyal4152)
- 🧑‍🏫 **Tech Lead at Kaizen** — mentoring students on AI and software engineering

---

## 📊 GitHub Stats

<p align="center">
  <img width="420" src="https://github-readme-stats.vercel.app/api?username=Pankaj4152&show_icons=true&theme=tokyonight&hide_border=true" />
  <img width="390" src="https://github-readme-streak-stats.herokuapp.com/?user=Pankaj4152&theme=tokyonight&hide_border=true" />
</p>

---

*3rd year CS undergrad @ MBM University, Jodhpur (2023–2027). Open to AI/ML roles and interesting problems.*
