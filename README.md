# Saurabh Salve

AI Engineer focused on **LLM systems, RAG pipelines, and production backends**.

I build AI products that survive real-world constraints: **latency, cost, and unreliable model outputs**.  
My work sits at the intersection of **research ideas and shippable systems**.

---

## What I’m Working On

- LLM-powered pipelines that convert large codebases into structured content and video
- Agentic systems with explicit validation, retries, and failure handling
- Async backend architectures for long-running AI workloads

I care less about demos and more about **systems that don’t break at scale**.

---

## Core Focus Areas

- Designing RAG systems that degrade gracefully under bad inputs
- Reducing inference cost and latency in multi-step LLM pipelines
- Clear ownership over clever abstractions
- Shipping > hype

---

## Flagship Projects

### Repo2Viral — Production LLM System
**Problem**  
Turning large GitHub repositories into high-quality documentation and social content is slow and inconsistent.

**What I Built**  
A production-grade RAG pipeline that parses repositories and generates structured, reviewable outputs.

**Why It’s Hard**
- LLM hallucinations on partial context
- Token cost explosion on large repos
- Long-running jobs that cannot block HTTP requests

**Key Engineering Decisions**
- Code-aware chunking and retrieval (not naive text splits)
- Async FastAPI workers for long-running jobs
- Rule-based validation layer before surfacing LLM output

**Stack**
FastAPI, Next.js, OpenAI API, Supabase, Docker

🔗 https://github.com/SAURABHSALVE/repo2viral

---

### Agentic AI Image Studio — Latency-First Design
**Problem**  
Multi-step diffusion pipelines are slow, fragile, and hard to scale.

**What I Built**  
A 9-agent workflow where agents iteratively refine prompts and validate outputs.

**Explicit Tradeoff**
- Used Latent Consistency Models (LCM) to achieve ~10× faster inference
- Accepted small quality loss in favor of iteration speed and throughput

**Why This Matters**
Most real products value **speed and reliability** over perfect outputs.

**Stack**
PyTorch, Diffusers, custom agent orchestration

🔗 https://github.com/SAURABHSALVE/image-generation

---

### Plant Disease Detection API — Classic ML, Shipped Properly
Production-ready computer vision service.

- Fine-tuned ResNet50 model
- 98% validation accuracy
- Dockerized REST API for reproducible deployment

**Stack**
Python, PyTorch, Docker

🔗 https://github.com/SAURABHSALVE/plant-disease-detection

---

## Technical Stack (Production Use Only)

**LLMs & GenAI**
- OpenAI API, RAG pipelines, prompt orchestration, agentic workflows

**Backend & Infra**
- Python, FastAPI, async workers, Docker
- AWS (EC2, Lambda, Bedrock), GCP (Vertex AI)

**Frontend**
- Next.js, Streamlit

**ML**
- PyTorch, CNNs, Computer Vision

---

## Experience

**IBM SkillsBuild — Data Science Intern**  
- Built churn prediction pipeline on 100k+ records  
- Automated analytics dashboards, reducing manual analysis ~40%

**AWS — Cloud Computing Intern**  
- Designed containerized EC2 deployments with autoscaling  
- Built serverless ETL pipelines handling 10k+ daily events

---

## Philosophy

- Systems should fail **predictably**
- Ownership beats cleverness
- Shipping beats talking

> “Talk is cheap. Show me the code.”

---

🔗 **LinkedIn:** https://linkedin.com/in/saurabhsalve99  
📫 **Email:** saurabhsalve9999@gmail.com
