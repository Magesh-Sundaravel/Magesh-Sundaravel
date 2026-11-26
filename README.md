# Magesh Sundaravel

**AI Engineer** · RAG · AI Agents · Voice Agents · Milan, Italy

I build LLM systems for production: retrieval pipelines, tool-calling agents and the data pipelines behind them. For a year I was the only engineer at a Milan fashion-tech startup, so I owned everything from design to evals, deployment and cost.

**Open to AI Engineer roles in Milan. Available now.**
[magesh094@gmail.com](mailto:magesh094@gmail.com) · [LinkedIn](https://linkedin.com/in/magesh-sundaravel)

---

## How I build

- **Evals before features.** Each agent gets a golden dataset and tracing (Langfuse) before I tune prompts.
- **Code where code is enough.** Validation, routing rules and anything that has to be correct stay deterministic. The LLM handles only what needs judgment.
- **Hybrid retrieval by default.** Dense + BM25 + fusion + reranking, measured with recall@k instead of judged by eye.
- **Cost is part of the design.** Route easy work to small models and save large models for hard cases.
- **Humans in the loop on purpose.** Agents flag ambiguity and escalate instead of guessing.

---

## Production experience: Lookalike S.r.l., Milan (2025 – 2026)

Sole AI engineer at a multimodal AI shopping startup.

- **Voice-to-product search.** Hybrid retrieval over a multi-million product catalog (multilingual embeddings, BM25, RRF, Cohere rerank). It clearly beat the vector-only baseline on recall@5.
- **Agentic customer support on Amazon Bedrock.** Reads tickets, calls order/shopping APIs, runs refunds and order updates, and escalates to humans. Haiku/Sonnet routing keeps cost per ticket low.
- **Catalog ETL.** Pulls Amazon + eBay data into one catalog, with rate-limit-aware retries and key-based deduplication.

---

## Featured work

### [creative-ops-agent](https://github.com/Magesh-Sundaravel/creative-ops-agent) · *active*
Takes a fashion/lifestyle creative brief from intake to agency handoff.
- Raw Claude API agent loop (no framework), with a coordinator, specialist subagents and a mock MCP server standing in for client systems (asset library, tracker, brand guidelines).
- **Design choice:** missing brief fields are computed in code, not by the model. Vague wording is raised as an ambiguity for a human, never filled in.
- Built with a Claude Code team setup: rules, hooks, subagents, CI.
- `Python 3.12 · Claude API · MCP · Pydantic · FastAPI · Streamlit · pytest · uv`

### [hotel-voice-agent](https://github.com/Magesh-Sundaravel/hotel-voice-agent) · *active*
24/7 receptionist that answers phone calls in Italian and English.
- ElevenLabs Agents handle speech and turn-taking. FastAPI tool webhooks handle availability, rates and booking create/modify/cancel, send Gmail confirmations with `.ics` invites, and take messages for reception.
- Bilingual IT/EN golden eval set. Langfuse tracing with phone numbers and emails masked.
- `ElevenLabs Agents · Telnyx SIP · Groq · FastAPI · Supabase · Langfuse · Docker`

### Also
- [**rag-platform**](https://github.com/Magesh-Sundaravel/rag-platform): hybrid retrieval, reranking, evaluation and observability in one RAG service.
- [**company-brain-ai-agent**](https://github.com/Magesh-Sundaravel/company-brain-ai-agent): LangGraph agent over CRM, ERP and call logs, built in a 6-hour hackathon.
- [**FinAI**](https://github.com/Magesh-Sundaravel/FinAI): expense agents with receipt OCR and Text-to-SQL.

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=flat&logo=postgresql&logoColor=white)

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=modelcontextprotocol&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat)

![AWS](https://img.shields.io/badge/AWS%20Bedrock-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

## GitHub activity
<p align="left"> <a href="https://github.com/Magesh-Sundaravel"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Magesh-Sundaravel&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D"> <img alt="GitHub streak" src="https://streak-stats.demolab.com?user=Magesh-Sundaravel&hide_border=true&date_format=j%20M%5B%20Y%5D"> </picture> </a> </p>
