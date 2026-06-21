<h1 align="center">Hi, I'm José Luis Perdomo 👋</h1>

<p align="center">
  <b>Backend &amp; AI Engineer</b> · Python · FastAPI · Multi-tenant AI systems<br>
  Founder and developer of <b>Habla</b>, an AI-powered customer service platform running in production.
</p>

<p align="center">
  <a href="https://github.com/JosePerdomoDeVega"><img src="https://img.shields.io/badge/Status-Open%20to%20opportunities-2ea44f?style=flat-square"></a>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
</p>

---

## About me

I'm a backend developer specialized in **Python** and **AI-powered systems**. Over the past year
I designed and built **Habla** from scratch — a SaaS platform that handles customer service with
AI across **voice calls, WhatsApp and email on behalf of each business**: it answers, looks up the
client's catalog and books appointments autonomously.

> The platform's code is private (it's a commercial product), but I've published an
> **architecture case study** and a **demo project** so you can see how I work.
> *(links below)*

---

## 🛠️ What I built in Habla

A distributed platform of **5 services** in Python, communicating over queues and deployed on AWS:

| Service | What it does | Key tech |
|---------|--------------|----------|
| **Real-time voice** | Handles calls with conversational AI (turn-taking, *barge-in*, low latency) | Twilio + OpenAI + ElevenLabs, WebSockets |
| **Messaging** | WhatsApp &amp; email chat with AI and conversation memory | Webhooks, LLM, Redis |
| **AI tooling** | MCP server that gives the AI access to the calendar and client data | FastMCP, multi-tenant JWT |
| **Job worker** | Background tasks (reminders, scheduled calls, cleanup) | SQS, handler-per-job pattern, idempotency |
| **Auth &amp; Payments** | Sign-up, login/2FA, payments, admin dashboard and public web | FastAPI, Stripe, PostgreSQL |

**Design patterns and decisions** I applied: **hexagonal architecture** (ports/adapters) in the
business services, **multi-tenancy** with per-client data isolation, **per-call state isolation**,
**asynchronous queue-based** communication, and **idempotency** in message processing.

---

## Stack

**Languages:** Python (primary), Java, SQL

**Backend:** FastAPI, FastMCP, async functions, WebSockets

**AI:** OpenAI, Claude, ElevenLabs (TTS), voice pipelines STT→reasoning→TTS, MCP

**Data:** SQL and NoSQL (PostgreSQL, Redis)

**Infra / Cloud:** AWS (EC2, RDS, ElastiCache, SQS, EventBridge, ECR, S3, Secrets Manager), Docker, Nginx

**Quality / Ops:** GitHub Actions (CI/CD), Logfire (observability)

---

## Featured projects

- 🏛️ **[Habla — Architecture Case Study](https://github.com/JosePerdomoDeVega/HablaArquitectureCaseStudy)** — System design, diagrams and technical decisions behind a production multi-tenant AI platform.
- 🧪 **[Demo: RAG Assistant](https://github.com/JosePerdomoDeVega/RagAssistantDemo)** — A small, multi-tenant retrieval-augmented support assistant built with FastAPI to show how I normally program with this stack.
- 🤖 **[Gender-Detector-with-ML](https://github.com/JosePerdomoDeVega/Gender-Detector-with-ML)** — Gender classification with ML (computer vision). One of my firsts encounters with Machine Learning. 

---

## Contact

<p align="left">
  <a href="mailto:perdomo.devega@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/jose-luis-perdomo/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
</p>
