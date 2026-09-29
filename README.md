<div align="center">

# Hi, I'm Aadhish 👋

### AI Engineer | GenAI Engineer | AI Automation Engineer

Building production RAG systems, multi-agent workflows, and LLM automation, from prototype to observability.

![Location](https://img.shields.io/badge/Chennai-India-blue?style=flat-square&logo=googlemaps&logoColor=white)
![Experience](https://img.shields.io/badge/Experience-1.5%2B%20years-success?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Agentic%20RAG%20%7C%20MCP%20%7C%20LLMOps-8A2BE2?style=flat-square)

[![JobLens Live](https://img.shields.io/badge/🔴%20Live%20Demo-JobLens-FF4B4B?style=for-the-badge)](https://joblens-gyha.onrender.com/app)

</div>

---

## 🧠 About Me

I'm an AI Engineer with 1.5+ years of experience shipping **production Generative AI** and **workflow automation**. I design agentic RAG systems, integrate them with real enterprise data sources, and instrument them so they can be debugged and measured in production.

- 🏢 Architected an **Enterprise AI Documentation Copilot** used by 50+ engineers and analysts
- 🔍 Built **JobLens**, a deployed AI career intelligence platform with RAG, agents, MCP, and LLMOps
- ⚙️ Designed an **n8n + LLM lead generation and enrichment** automation pipeline
- 📐 I care about evaluation, observability, and cost tracking as much as the model itself
- 🎓 B.Tech in Computer Science

---

## 💼 Experience

### AI Engineer, Internal AI Platform · Fipsar Solutions, Chennai
*Jan 2025 – Present*

**Enterprise AI Documentation Copilot**: a unified AI knowledge platform across SharePoint, Snowflake, and enterprise BI data.

- 🤖 **Agentic RAG** with LangGraph-orchestrated multi-agent workflows, semantic search, and project-aware retrieval
- 📝 Lets developers generate **BRDs, functional specs, and test cases**, cutting manual documentation effort by **40%** and saving teams **15+ hours weekly**
- 🔌 Enterprise integrations via **Microsoft Graph API**, Snowflake connector, and platform APIs, indexing **10,000+ documents** into a centralized **Qdrant** knowledge base
- 🧩 Exposed internal tools and data sources as standardized **MCP servers** for agent-tool interoperability
- 📡 Full **LangSmith** tracing of every LLM call, agent step, and tool invocation, leading to a **30% reduction** in issue resolution time

---

## 🚀 Featured Projects

### 🔍 [JobLens](https://github.com/sAadhish/joblens): AI Career Intelligence Platform  ·  [Live Demo](https://joblens-gyha.onrender.com/app)

An end-to-end GenAI platform for multi-document comparison across resumes and job descriptions, built from scratch and then re-engineered with production frameworks.

```
Query → Classifier → Router → Hybrid Retrieval (Vector + BM25) → Cross-Encoder Rerank → LLM → Self-check → Answer
                                        ↑                                                   │
                                        └──────────────── Persistent Memory ────────────────┘
```

- 🧱 **RAG from scratch:** semantic chunking, dense vector search, BM25 hybrid retrieval, cross-encoder reranking
- 🔁 **LangChain refactor** (OOP architecture) on **Qdrant Cloud**, at feature parity with the hand-built version for direct implementation comparison
- 🧠 **LangGraph agents** with multi-step reasoning, tool calling, self-correcting RAG, and persistent memory
- 🔌 **MCP integration** exposing retrieval and analysis as standard tool endpoints for any MCP-compatible client
- 📊 **Evaluation system** measuring Hit Rate, MRR, Precision@K, and Faithfulness with automated regression detection, reaching an **85% overall score** across 3 evaluation runs
- 🛰️ **Observability:** LangSmith tracing, custom callback handlers, latency, token, and cost tracking, prompt version management
- 🚢 **Deployment:** FastAPI with authentication, structured logging, caching, and Docker, following LLMOps best practices

**Stack:** `Python` · `FastAPI` · `LangChain` · `LangGraph` · `LangSmith` · `Qdrant` · `MCP` · `Cross-Encoder` · `RAGAS` · `Docker`

---

### ⚙️ AI-Powered Lead Generation & Enrichment Automation

An end-to-end automation that finds, enriches, and qualifies B2B leads with LLMs.

- 🎯 Automated prospect discovery by geography, industry, company size, and decision-maker role
- 🔗 **Apollo.io** APIs for prospect search plus contact and company enrichment
- 🧹 Normalization, filtering, validation, missing-value handling, and **deduplication** before storage
- 🧠 **LLM-based enrichment** producing structured lead insights and context-aware business summaries
- 🔄 Modular pipeline that runs manually, via **webhook**, or on a **schedule**

**Stack:** `n8n` · `Apollo.io` · `REST APIs` · `LLMs (Groq)` · `Google Sheets`

---

## 🛠️ Tech Stack

**Languages & Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

**LLM Frameworks & Agents**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-7C3AED?style=for-the-badge&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)

**Retrieval & Databases**

![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)

**Automation, DevOps & Observability**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-Evaluation-orange?style=for-the-badge)

**Core GenAI Concepts:** Agentic RAG · Hybrid Search (Vector + BM25) · Cross-Encoder Reranking · Tool Calling · Memory Systems · Prompt Engineering · Context Window Management · Faithfulness Evaluation · LLMOps

---

## 🗺️ What's Next

| Status | Project |
|:------:|---------|
| ✅ | **JobLens**: deployed and live |
| 🔨 | **Financial Intelligence Co-Pilot**: next flagship project |
| 🔜 | **Multi-agent systems**: orchestration and collaboration patterns |
| 🧪 | **Algorithmic trading bot**: Python backtesting with Supertrend on Binance data |

---

## 📫 Let's Connect

I'm open to **GenAI Engineer / AI Engineer** roles at product-based companies and AI-native startups.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-aadhish--s-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aadhish-s)
[![Email](https://img.shields.io/badge/Email-aadhishs007@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aadhishs007@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-sAadhish-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sAadhish)

---

## 📊 GitHub Stats

<div align="center">

![Aadhish's GitHub stats](https://github-readme-stats.vercel.app/api?username=sAadhish&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sAadhish&layout=compact&theme=tokyonight&hide_border=true)

![Streak](https://streak-stats.demolab.com?user=sAadhish&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*"Retrieval finds the facts. Agents act on them. Evaluation keeps them honest."*

</div>
