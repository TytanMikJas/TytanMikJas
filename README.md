<h1 align="center">Mikołaj Jastrzębski</h1>

<p align="center">
  <strong>AI Research &amp; Engineering</strong><br>
  Generative video · Archival film restoration · Agentic systems in production
</p>

<p align="center">
  <a href="https://www.mikjas.com"><img src="https://img.shields.io/badge/Portfolio-mikjas.com-0A0A0A?style=flat-square&logo=safari&logoColor=white" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/mikołaj-jastrzębski"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:mikjas02@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<p align="center">
  🎓 M.Sc. in Artificial Intelligence — <strong>Wrocław University of Science and Technology</strong> · GPA 5.0/5.0, Highest Distinction
</p>

---

## 📄 Research

First-author work on restoring century-old film — two papers under review, plus a deployment with two Polish cultural institutions.

### DART: A Degradation-Aware Recurrent Transformer for Archival Film Restoration

<a href="https://arxiv.org/abs/2607.21219"><img src="https://img.shields.io/badge/arXiv-2607.21219-b31b1b?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv"></a>
<img src="https://img.shields.io/badge/ACCV_2026-submitted-informational?style=flat-square" alt="ACCV 2026">

A recurrent transformer that predicts a soft defect mask and propagates it through time — reasoning explicitly about *where* footage is damaged and *how severely*, instead of reconstructing frames blindly.

- **State-of-the-art perceptual quality** on real archival benchmarks, outperforming BasicVSR++, RTN, DeepRemaster and MambaOFR
- **6.6M parameters at 0.35 GB** — the most memory-efficient model in the comparison
- Multi-scale Dilation Pyramid MaskNet with direct mask supervision and AdaLN-Zero degradation conditioning
- Trained multi-node on HPC clusters (SLURM, DDP)

### AbsoluteDegradation: A Physics-Inspired Synthetic Film-Degradation Pipeline and Archival Benchmark

<a href="https://arxiv.org/abs/2607.02131"><img src="https://img.shields.io/badge/arXiv-2607.02131-b31b1b?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv"></a>
<img src="https://img.shields.io/badge/NeurIPS_2026_D&B-submitted-informational?style=flat-square" alt="NeurIPS 2026 Datasets & Benchmarks">

A degradation pipeline that models the full analog-to-digital chain — signal-dependent grain, mean-reverting (Ornstein–Uhlenbeck) gate weave, parametric scratches — paired with a large real-world archival benchmark.

- **First synthesis method to jointly model all 7 analog artifact families** with temporal coherence and a severity curriculum
- **81,576-frame benchmark** curated from 30 public-domain films (1896–1918, Library of Congress)
- Models trained on the pipeline generalize measurably better to real footage, and expose failure modes of prior methods

> 🔒 Both papers are under review. Code and full results will be released on acceptance.

### 🏛️ Real-world deployment

Self-initiated restoration collaborations with **Narodowe Archiwum Cyfrowe** (Polish National Digital Archive) and the **Museum of Modern Art in Warsaw** — restoring footage from their collections, with positive institutional feedback.

---

## 🚀 What I work on

**Research.** Computer vision and generative modeling for video — temporal consistency, detail reconstruction, and degradation modeling for archival footage.

**Production ML.** At Grid Dynamics I built a hierarchical multi-agent system (Google ADK) for automated B2B sales research, and a production-grade Langfuse observability suite with full-lifecycle tracing, prompt versioning, and a dual-evaluator framework. Cut inference cost 30% via prompt caching and instance selection, and latency 15% via async agent execution. Shipped a config-driven agent starter-kit that became the internal standard, taking new agents from days to hours to production.

**End-to-end.** A full-stack background (React, Angular, NestJS, Spring Boot) means I don't just train models — I ship them as scalable, production-ready systems on GCP and Azure.

---

## 🛠️ Stack

| Area | Tools |
|------|-------|
| **ML & Research** | Python · PyTorch · OpenCV · NumPy · pandas · Scikit-learn |
| **Domains** | Computer Vision · Generative Models · Video Restoration · Self-Supervised Learning |
| **Agents & LLMs** | Google ADK · Langfuse · Pydantic · RAG · Prompt versioning &amp; evaluation |
| **MLOps** | GCP · Azure · Docker · Linux · CI/CD · SLURM &amp; multi-node DDP · W&B · DVC |
| **Backend** | Java · TypeScript · NestJS · Spring Boot · PostgreSQL |
| **Frontend** | React · Angular · TypeScript · TailwindCSS |

---

## 🎤 Talks &amp; Certifications

- 🎤 **ML in PL 2025** — presented *Generative Image Inpainting with Self-Supervised Learning* (student workshop)
- ☁️ **Google Cloud Associate Cloud Engineer**
- 🧠 **Deep Learning Specialization** — DeepLearning.AI
- 🇬🇧 **IELTS C1** — Academic English

---

## 🏆 Hackathons

| Result | Event |
|--------|-------|
| 🥇 **1st Place** | Hack The Climate (PFR & NordicEdge) — €10,000 |
| 🥇 **1st Place** | EBEC Challenge (2022) |
| 🥈 **2nd Place** | Grow Up Tech #4 (AIP PWr) |
| 🥈 **2nd Place** | Hack2React (PFR) |
| 🥈 **2nd Place** | EBEC Challenge Poland (2023) |

---

<p align="center">
  <a href="https://www.mikjas.com">mikjas.com</a> ·
  <a href="mailto:mikjas02@gmail.com">mikjas02@gmail.com</a> ·
  <a href="https://linkedin.com/in/mikołaj-jastrzębski">LinkedIn</a>
</p>
