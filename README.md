# Hey, I'm Saurabh 👋

**AI Engineer building production-grade systems that survive latency, cost, and unreliable model outputs.**

I design and ship AI systems that sit between **research ideas and real products**. My focus isn't demos — it's **systems that don't fall apart in production**.

---

## 🔨 What I'm Building

- **LLM pipelines** that convert large codebases into structured content & video
- **Agentic systems** with validation, retries, and explicit failure handling
- **Async backends** for long-running AI workloads

---

## 🎯 Engineering Focus

```
→ RAG systems that degrade gracefully under bad inputs
→ Reducing token cost & latency in multi-step LLM workflows
→ Clear ownership over clever abstractions
→ Shipping > hype
```

---

## 🚀 Featured Projects

### [Repo2Viral](https://github.com/SAURABHSALVE/repo2viral) — Production LLM System
Turning large GitHub repositories into usable documentation & content

**The Challenge:**
- Partial context causes hallucinations
- Token cost explodes on large repos
- Long-running jobs can't block HTTP requests

**The Solution:**
- Code-aware chunking & retrieval (not naive text splits)
- Async FastAPI workers for long jobs
- Rule-based validation before surfacing LLM output

`FastAPI` `Next.js` `OpenAI API` `Supabase` `Docker`

---

### [Agentic AI Image Studio](https://github.com/SAURABHSALVE/image-generation) — Latency-First Design
Multi-agent system for automated prompt refinement & output control

**Explicit Tradeoff:**
- Used **Latent Consistency Models (LCM)** → ~10× faster inference
- Accepted slight quality loss for speed & throughput

Real products value **speed and reliability**, not perfect outputs.

`PyTorch` `Diffusers` `Agent Orchestration`

---

### [Plant Disease Detection API](https://github.com/SAURABHSALVE/plant-disease-detection) — ML, Shipped Properly
Production-ready computer vision service

- Fine-tuned ResNet50 (98% validation accuracy)
- Dockerized REST API
- Designed for deployment, not notebooks

`Python` `PyTorch` `Docker`

---

## 🛠 Tech Stack

**GenAI & LLMs**  
OpenAI API · RAG Pipelines · Prompt Orchestration · Agentic Workflows

**Backend & Infrastructure**  
Python · FastAPI · Async Workers · Docker · AWS (EC2, Lambda, Bedrock) · GCP (Vertex AI)

**Frontend**  
Next.js · Streamlit

**ML**  
PyTorch · CNNs · Computer Vision

---

## 💡 Engineering Philosophy

```python
def build_systems():
    principles = {
        "reliability": "Systems should fail predictably",
        "ownership": "Ownership beats cleverness",
        "execution": "Shipping beats talking"
    }
    return principles
```

> **"Talk is cheap. Show me the code."**

---

## 📊 Problem-Solving

- **90 LeetCode problems solved** — [Profile](https://leetcode.com/u/Saurabhsalve9999/)
- Focus on algorithms, data structures, and system design thinking

---

## 💼 Experience Highlights

**IBM SkillsBuild** — Data Science Intern  
→ Built churn prediction pipeline on 100k+ records  
→ Automated dashboards → ~40% reduction in manual analysis

**AWS** — Cloud Computing Intern  
→ Containerized EC2 deployments with autoscaling  
→ Serverless ETL pipelines handling 10k+ daily events

---

## 📫 Let's Connect

Building something interesting? Let's talk about **systems that work in production**.

[![GitHub](https://img.shields.io/badge/GitHub-SAURABHSALVE-181717?style=for-the-badge&logo=github)](https://github.com/SAURABHSALVE)
[![LeetCode](https://img.shields.io/badge/LeetCode-Saurabhsalve9999-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/Saurabhsalve9999/)

---

<div align="center">
  
**Systems Engineer · Not a Demo Builder**

*Focused on what survives production, not what looks good in slides.*

</div>
