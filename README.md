# Hi, I'm Magesh 👋

**AI Engineer · RAG · AI Agents · Agentic AI** · Pavia / Milan, Italy

> AI systems that ship, not just prototypes.

I build production LLM systems: hybrid retrieval pipelines, tool-calling agents, voice agents, and the data pipelines that feed them. I spent a year as the **sole engineer** at a Milan fashion-tech startup, taking AI features from idea to production.

🟢 **Open to AI Engineer / GenAI Engineer roles in Milan. Available now.**

---

## 💼 Experience

**AI Engineer · Lookalike S.r.l. (Multimodal AI Shopping), Milan** · *May 2025 – May 2026*

- **Voice-driven product search:** designed and deployed a hybrid retrieval pipeline (multilingual embeddings + BM25 + RRF fusion + reranking) over a multi-million product catalog, with a large recall gain over a vector-only baseline.
- **Catalog ETL:** built the pipeline that pulls Amazon and eBay product data into one unified catalog, with rate-limit retries and deduplication.
- **Agentic customer support:** built a support agent on Amazon Bedrock that reads tickets, calls order/shopping APIs, handles order updates, refunds and human escalation, and routes between models to keep costs down.

---

## 🚀 Featured Projects

### 🎨 [creative-ops-agent](https://github.com/Magesh-Sundaravel/creative-ops-agent) · *in progress*
Agentic system that takes a fashion/lifestyle creative brief from intake to agency handoff.
- Extracts structured fields from messy briefs, lists what the client left out, and flags when a human must review. Missing fields are computed in code, not guessed by the model.
- Hand-written agent loop on the Claude API (no frameworks), with a coordinator, specialist subagents and a mock MCP client stack.
- **Stack:** Python · Claude API · MCP · Pydantic · FastAPI · Streamlit · pytest

### 📞 [hotel-voice-agent](https://github.com/Magesh-Sundaravel/hotel-voice-agent) · *in progress*
24/7 AI hotel receptionist that answers phone calls in Italian and English.
- ElevenLabs Agents handle speech and turn-taking. FastAPI tool webhooks check availability and rates, create/modify/cancel bookings, send Gmail confirmations with `.ics` invites, and take messages for reception.
- Langfuse tracing with PII masking, plus a bilingual (IT/EN) eval dataset.
- **Stack:** ElevenLabs Agents · Telnyx SIP · Groq · FastAPI · Supabase · Gmail · Langfuse · Docker

### 🔎 [rag-platform](https://github.com/Magesh-Sundaravel/rag-platform)
RAG platform with hybrid retrieval, vector search, reranking, evaluation and observability.

### 💸 [FinAI](https://github.com/Magesh-Sundaravel/FinAI)
Finance AI agents that parse, categorize and analyze expenses, with receipt OCR and a Text-to-SQL agent.

### 🧠 [company-brain-ai-agent](https://github.com/Magesh-Sundaravel/company-brain-ai-agent)
Agentic assistant over CRM, ERP, call logs and internal docs, built with LangGraph, FastAPI and RAG. Delivered as a working multi-source agent in a **6-hour hackathon**.

---

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**LLMs & Agents**
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat)

**Backend, Data & Voice**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat&logo=elevenlabs&logoColor=white)
![WhatsApp Business API](https://img.shields.io/badge/WhatsApp%20Business%20API-25D366?style=flat&logo=whatsapp&logoColor=white)

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Amazon Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-FF9900?style=flat&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

## 🎓 Education & Certifications

- **Master's Degree, Industrial Automation**: Università di Pavia (2020 – 2024)
- **Anthropic:** Introduction to MCP · Building with the Claude API · Claude Code in Action · AI Fluency
- **Coursera:** Machine Learning Specialization

🌍 English (full professional) · Italian (conversational)

---

## 📫 Contact

[![Email](https://img.shields.io/badge/Email-magesh094%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:magesh094@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-magesh--sundaravel-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/magesh-sundaravel)
