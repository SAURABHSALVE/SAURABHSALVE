<div align="center">

# Saurabh Salve

### AI Engineer · LLM Systems · RAG · Full-Stack

Building **production-grade AI systems** that survive  
**latency, cost, and unreliable model outputs**

<br/>

<a href="https://linkedin.com/in/saurabhsalve99">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:saurabhsalve9999@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat&logo=gmail&logoColor=white"/>
</a>

</div>

---

## 🧠 What I Do

I design and ship AI systems that sit between **research ideas and real products**.

My focus is not demos — it’s **systems that don’t fall apart in production**.

**Currently building:**
- LLM pipelines that convert large codebases into structured content & video
- Agentic systems with validation, retries, and explicit failure handling
- Async backends for long-running AI workloads

---

## 🔍 Engineering Focus

- RAG systems that **degrade gracefully** under bad inputs  
- Reducing **token cost & latency** in multi-step LLM workflows  
- Clear ownership over clever abstractions  
- Shipping > hype  

---

## 🚀 Flagship Projects

### 🟣 Repo2Viral — Production LLM System
> Turning large GitHub repositories into usable documentation & content

**Why it’s hard**
- Partial context causes hallucinations  
- Token cost explodes on large repos  
- Long-running jobs can’t block HTTP requests  

**What I built**
- Code-aware chunking & retrieval (not naive text splits)
- Async FastAPI workers for long jobs
- Rule-based validation before surfacing LLM output

**Stack**
`FastAPI · Next.js · OpenAI API · Supabase · Docker`

🔗 https://github.com/SAURABHSALVE/repo2viral

---

### 🟣 Agentic AI Image Studio — Latency-First Design
> Multi-agent system for automated prompt refinement & output control

**Explicit tradeoff**
- Used **Latent Consistency Models (LCM)** → ~10× faster inference  
- Accepted slight quality loss for speed & throughput  

**Why this matters**
Real products value **speed and reliability**, not perfect outputs.

**Stack**
`PyTorch · Diffusers · Agent Orchestration`

🔗 https://github.com/SAURABHSALVE/image-generation

---

### 🟣 Plant Disease Detection API — ML, Shipped Properly
> Production-ready computer vision service

- Fine-tuned ResNet50 (98% validation accuracy)
- Dockerized REST API
- Designed for deployment, not notebooks

**Stack**
`Python · PyTorch · Docker`

🔗 https://github.com/SAURABHSALVE/plant-disease-detection

---

## 🛠 Tech I Use in Production

**GenAI & LLMs**
- OpenAI API, RAG pipelines, prompt orchestration, agentic workflows

**Backend & Infra**
- Python, FastAPI, async workers
- Docker, AWS (EC2, Lambda, Bedrock), GCP (Vertex AI)

**Frontend**
- Next.js, Streamlit

**ML**
- PyTorch, CNNs, Computer Vision

---

## 💼 Experience

**IBM SkillsBuild — Data Science Intern**  
- Built churn prediction pipeline on 100k+ records  
- Automated dashboards → ~40% reduction in manual analysis  

**AWS — Cloud Computing Intern**  
- Containerized EC2 deployments with autoscaling  
- Serverless ETL pipelines handling 10k+ daily events  

---

## 🧭 Engineering Philosophy

- Systems should fail **predictably**
- Ownership beats cleverness
- Shipping beats talking

<div align="center">

**“Talk is cheap. Show me the code.”**

</div>
