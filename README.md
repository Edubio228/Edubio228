# Hi, I'm Emmanuel Edubio

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=00ADB5&size=30&center=true&vCenter=true&width=800&lines=MLOps+Engineer;Production+AI+Infrastructure;Backend+%26+System+Design;Kubernetes+%7C+Model+Serving;QwenOps+%7C+Incident+Autopilot)](https://git.io/typing-svg)

![MLOps](https://img.shields.io/badge/MLOps-Engineer-black?style=for-the-badge)
![Backend](https://img.shields.io/badge/Backend-Python%20%7C%20FastAPI%20%7C%20Django-darkblue?style=for-the-badge)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-blue?style=for-the-badge)
![Model Serving](https://img.shields.io/badge/Model-Serving%20%7C%20Triton-purple?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Production%20AI%20Systems-green?style=for-the-badge)

**MLOps Engineer** and **Backend Developer** bridging the gap between AI research and production infrastructure. I build systems that are deployable, scalable, observable, and—most importantly—reliable.

---

## About Me

I take AI models from Jupyter notebooks and turn them into **production services that handle real traffic**. With a strong foundation in backend engineering and system design, I focus on the infrastructure that makes AI useful in the real world.

My work centers on:

- **Model Serving & Optimization**: Deploying models with low latency and high throughput (FastAPI, Triton, BentoML)
- **Orchestration**: Managing containerized workloads on Kubernetes with autoscaling and GPU scheduling
- **MLOps Pipelines**: CI/CD for models, experiment tracking, and versioned deployments (MLflow, Kubeflow)
- **Observability**: Structured logging, metrics, and alerting to ensure system health (Prometheus, Grafana)
- **AI Agent Orchestration**: Building multi-agent systems with human-in-the-loop safety checkpoints (LangGraph)

**Philosophy**: AI systems should be *boring but bulletproof*. They should work predictably, fail gracefully, and integrate seamlessly into existing workflows.

---

## Featured Projects

### 🔥 QwenOps: Incident Autopilot
*(Qwen Global AI Hackathon 2026 - Track 4)*

**Problem**: On-call engineers waste 10+ minutes just gathering context during incidents.

**Solution**: An AI-powered SRE assistant that handles the first 5 minutes of an incident:
- Fetches Kubernetes logs and metrics in real-time
- Uses Qwen API to hypothesize root cause in < 3 seconds
- Generates safe mitigation commands with an `is_destructive` safety flag
- Drafts post-mortem reports automatically

**Tech Stack**: FastAPI, Qwen API, Kubernetes Python Client, Redis, Docker, Alibaba Cloud ECS

[Live Demo](http://your-deployed-url) | [GitHub](https://github.com/edubio228/qwenops) | [Devpost](https://qwen.devpost.com)

---

### 📊 AI Knowledge Assistant (RAG System)
*(Production RAG for Internal Documentation)*

**Problem**: Teams spend hours searching wikis, PDFs, and Slack history for answers.

**Solution**: A retrieval-augmented generation system with:
- Document ingestion and semantic chunking
- Vector database storage (Pinecone/Chroma)
- Natural language Q&A with source citations
- Human feedback loop for continuous quality improvement

**Tech Stack**: FastAPI, LangChain, Qwen API, Vector DB, Redis, Docker, AWS S3

[GitHub](https://github.com/edubio228/rag-knowledge-assistant)

---

### 🤖 Multi-Agent Workflow Orchestrator
*(Autonomous Research Pipeline)*

**Problem**: Complex tasks require multiple specialized steps (research, extraction, summarization).

**Solution**: A LangGraph-based system with:
- 3 specialized agents (Researcher, Extractor, Summarizer)
- Human-in-the-loop checkpoints for validation
- Persistent state management across sessions
- Async task queue for long-running jobs (Celery + Redis)

**Tech Stack**: LangGraph, FastAPI, Celery, Redis, PostgreSQL, Docker Compose

[GitHub](https://github.com/edubio228/multi-agent-orchestrator)

---

## Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Backend Engineering
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### MLOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Alibaba Cloud](https://img.shields.io/badge/Alibaba_Cloud-FF6A00?style=for-the-badge&logo=alibabacloud&logoColor=white)

### AI & LLM Frameworks
![Qwen](https://img.shields.io/badge/Qwen-FF6A00?style=for-the-badge&logo=alibabacloud&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### Observability & Monitoring
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK-005571?style=for-the-badge&logo=elasticstack&logoColor=white)

---

## Engineering Philosophy

### Production-First
Every system is designed for reliability—not just functionality. I evaluate latency, cost, failure modes, and rollback strategies before writing a single line of code.

### Infrastructure as Code
Infrastructure is defined in code (Terraform, Helm, Docker Compose). Manual clicks in cloud consoles are a liability.

### Observability by Design
If it can't be monitored, it's not production-ready. Every system exposes metrics, structured logs, and traces.

### Safe AI
AI systems need guardrails. I enforce human approval, destructive-command flags, rate limiting, and graceful fallbacks to prevent unintended harm.

### Cost Awareness
AI should be intelligent *and* economical. I optimize token usage, use cheaper models for simple tasks, and cache aggressively.

---

## GitHub Stats

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=edubio228&layout=compact&theme=github_dark)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/emmanuel-edubio/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Website-black?style=for-the-badge)](https://emmanuel-edubio.lovable.app/)
[![QwenOps](https://img.shields.io/badge/QwenOps-Hackathon%20Project-orange?style=for-the-badge)](https://github.com/edubio228/qwenops)

---

## 📌 Open to Opportunities

I'm actively seeking **MLOps Engineer**, **AI Platform Engineer**, and **Production AI Systems** roles where I can build the infrastructure that makes AI reliable, scalable, and impactful.

If you're building AI infrastructure or need someone to take models from notebooks to production, let's talk.

---

⭐ *Built with ❤️ for production-grade AI.*
