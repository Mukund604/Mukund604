# Hi, I'm Mukund Ojha

Software engineer building production AI systems. Lead App Engineer at TopTutors, founder of [GradeRight.org](https://graderight.org), and MS CS student at UC Santa Cruz (graduating December 2026).

[![Portfolio](https://img.shields.io/badge/Portfolio-mukundojha.dev-000000?style=for-the-badge)](https://mukundojha.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mukund604/)
[![Email](https://img.shields.io/badge/Email-muojha@ucsc.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muojha@ucsc.edu)

---

## What I'm working on

**TopTutors, Lead App Engineer.** I lead a team of 4 engineers on a multitenant B2B school platform built with Next.js, React, PostgreSQL and AWS. I built its AI assessment pipeline, which turns exam PDFs into graded tests and cut exam setup from hours to minutes, plus a tutor matching engine that scores each pair on 8 weighted dimensions.

**[GradeRight.org](https://graderight.org), Founder.** An AI grading product with 30,000+ users that earns revenue, built and run by me alone. Light tasks go to a small model and heavy grading goes to self hosted models on vLLM. Every prompt or model change has to pass a golden set evaluation before it goes live, which keeps human overrides under 10%.

## Research

**Commit Before Trust: Transactional Shared Memory for Multi-Agent LLMs** (under review)
Agents never write to shared memory directly. They propose updates, a guard commits or rejects each one, and checkpoints roll back bad ones. Against full history passing on HotpotQA, shared memory with guarded commits cut tokens 62% and raised exact match from 0.50 to 0.54, and the guard caught 50 of 50 injected contradictions.

**[Diagnosing How Frontier LLMs Fail at Lean: A miniF2F-v2 Evaluation Study](https://github.com/Mukund604/CSE290_LLM_Evaluation_Using_Lean)** (under review)
An evaluation harness that checks every model proof with Lean, across 222 runs on 30 problems. A common 180 second timeout understated pass rates 3x.

## Shipped and shipping

* **SlugMarket**: a UCSC only marketplace, live on the App Store. Swift, Supabase, row level security, real time chat and push notifications.
* **VagBay**: a marketplace and community app for Volkswagen Group enthusiasts, launching soon. React Native, NestJS, PostgreSQL, Redis.
* **Avaada Energy** (2023 to 2025): first AI/ML hire. Java and Python services running ML models across 32+ solar sites saved $50K+ a year, and fleet alerting raised uptime 18%.

## Toolkit

| | |
| :--- | :--- |
| **Languages** | Python, TypeScript, Java, SQL, Swift |
| **AI** | LLM APIs, LangGraph, vLLM, RAG, MCP, PyTorch |
| **Backend and infra** | FastAPI, NestJS, Next.js, PostgreSQL, Redis, Docker, Kubernetes, AWS |

## Education

* **M.S. in Computer Science and Engineering**, UC Santa Cruz, GPA 3.92/4.00, graduating December 2026
* **B.Tech in Computer Science Engineering**, Chitkara University, GPA 4.0/4.0
