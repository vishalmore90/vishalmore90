**Student Developer** 

## About

- I build things that need to be fast, reliable, and scalable. Currently going deep on **Kubernetes** and **cloud-native infrastructure**, while keeping a strong foundation in Go and Python for backend systems.
- Focused on **Cloud & DevOps** — container orchestration, distributed systems, and infrastructure that doesn't fall over
- Working towards building production-grade software while still in college — messy process, learning a lot

---

## Projects

| Project | Description | Stack | Status |
|---|---|---|---|
| [**PodWhisper**](https://github.com/vishalmore90/PodWhisper) | Autonomic Kubernetes failure-analysis agent built on the **MAPE-K control loop**. Watches clusters in real-time, intercepts pod failures (CrashLoopBackOff / ImagePullBackOff), and delivers RAG-augmented root-cause diagnoses with per-stage MTTR instrumentation. Achieved **88% MTTR reduction** (6.8s vs 60s+ manual). Research paper targeting SREcon → ACM SoCC. | `Go` `Python` `FastAPI` `ChromaDB` `Gemini 2.5 Flash` `Kubernetes` `Prometheus` `Docker` | 🟡 Active Research |
| [**DevOps-Kubernetes-AI-Agent**](https://github.com/vishalmore90/DevOps-Kubernetes-AI-Agent) | AI-powered SRE & troubleshooting platform (**InsForge**) that automatically connects to Kubernetes clusters, collects debugging evidence (pods, logs, events, deployments, services), and uses LLMs to deliver root cause analyses and remediation suggestions with confidence scoring. Features a real-time frontend dashboard with Socket.IO live updates. | `Python` `FastAPI` `React` `Socket.IO` `OpenRouter` `Llama-3` `Claude` `GPT` `Docker Compose` | 🟢 Complete |
| [**AI-Kubernetes-Upgrader**](https://github.com/vishalmore90/AI-Kubernetes-Upgrader) | Automated, evidence-based Kubernetes **upgrade feasibility & risk assessment engine**. Runs a 17-step analysis covering API deprecations, CRD/controller compatibility, webhooks, networking, storage, and security. Generates a 10-area Risk Matrix, a Readiness Score (0–100), and a Confidence Score with an upgrade decision (APPROVED / CONDITIONAL / NOT RECOMMENDED). Includes an interactive Flask web dashboard. | `Python` `Flask` `kubectl` `pytest` | 🟢 Complete |
| [**Article-WebScraping**](https://github.com/vishalmore90/Article-WebScraping) | Python script that scrapes technology articles from **The Guardian** via their public API. Fetches article data, extracts titles and full content, and saves each article to separate text files for downstream processing or NLP workflows. | `Python` `The Guardian API` `REST` | 🟢 Complete |
| [**Gemini-ChatBot**](https://github.com/vishalmore90/Gemini-ChatBot) | A **Streamlit** web interface that enables real-time conversational interactions with Google's **Gemini-Pro** GenerativeAI model. Users can ask questions or engage in dialogue, receiving responses from the Gemini-Pro model in a clean chat UI. | `Python` `Streamlit` `Google Gemini-Pro` `Google GenerativeAI API` | 🟢 Complete |
| [**Portfolio**](https://vishal.vercel.app) | Personal portfolio website showcasing projects, skills, and experience as an SRE & AI/ML Engineer. | `Next.js` `Vercel` | 🟢 Live |

---
