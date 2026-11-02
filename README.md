<img src="https://krishkrkashyap.github.io/assets/krish-kumar-og-card.jpg" alt="Krish Kumar (krishkrkashyap) — AI Engineer, Ahmedabad, India" width="100%">

# Krish Kumar

**AI Engineer** · Ahmedabad, Gujarat, India · [`krishkrkashyap`](https://github.com/krishkrkashyap)

[![Portfolio](https://img.shields.io/badge/Portfolio-krishkrkashyap.github.io-00ff41?style=for-the-badge&logo=github&logoColor=white)](https://krishkrkashyap.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-krishkrkashyap-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/krishkrkashyap)
[![X](https://img.shields.io/badge/X-@krishkrkashyap-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/krishkrkashyap)
[![Instagram](https://img.shields.io/badge/Instagram-@krishkrkashyap-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/krishkrkashyap)
[![Email](https://img.shields.io/badge/Email-krishkrkashyap@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:krishkrkashyap@gmail.com)

---

I ship LLM systems into daily operational use, not demos.

I design multi-provider agent architectures — tool calling, RAG over pgvector, multilingual
NLU, scheduled autonomous workflows — and build the backend, data and interface layers they
depend on. At **Cafe Uppercrust Group** I own internal engineering for a 12-outlet bakery,
restaurant and catering group, and have delivered **40+ production systems in six months**.

Before that I applied the same stack in fintech at **Junomoneta Finsol**: LLM-driven research
automation that cut manual analysis time 60%, and ML and statistical pipelines over 5+ years
of market data.

I'm deliberate about correctness in money, auth and data paths.

---

## What I've built

| | |
|---|---|
| **WhatsApp AI Operations Assistant** | Conversational agent used daily by **~500 staff**. An 11-tool agent layer with per-tool argument schemas and admin-only gating, so the model answers from live operational data instead of improvising. RAG over a company knowledge base; NLU across English, Hindi, Hinglish and Gujarati. `FastAPI` `PostgreSQL + pgvector` `Redis` |
| **Petpooja POS MCP Server** | A Model Context Protocol server exposing a commercial POS platform as schema-validated, AI-callable tools — replacing one-off analysis scripts with a conversational interface over live business data. `Python` `MCP` |
| **Provider-agnostic LLM layer** | Anthropic, OpenAI, Groq and Gemini behind one interface, with a deterministic keyword fallback, so operations survive a degraded provider or an exhausted quota. |
| **POS-to-Tally accounting bridge** | Replaced a paid vendor connector for 12 outlets. Balanced Tally XML vouchers per payment mode per day, exact-arithmetic money handling, per-day idempotency, behind 11 test suites. |
| **k-pos** | Offline-first restaurant POS replacing a paid SaaS till. Integer-paise money with basis-point taxes, price snapshots, transactional order mutations under optimistic concurrency. `TypeScript` `Fastify` `SQLite WAL` `React` |
| **Margin-leakage forensic audit** | A full year of transaction data through a staged pandas pipeline on Parquet. Quantified recurring leakage and — the finding that mattered — identified material value flowing through controls that did not exist. Shipped with a monitoring spec and a runnable control script. |
| **Biometric attendance kiosk** | Fingerprint templates never leave the device: on-device 1:N matching, offline punch queueing, server-side geofence authority rather than trusting the client. `Kotlin` `Jetpack Compose` `CameraX` |

<sub>Much of the above is internal company work and not public. The repositories below are what I can share.</sub>

---

## Stack

**AI / LLM**
`Anthropic Claude API` `OpenAI` `Gemini` `Groq` `Ollama` · multi-provider routing with fallback ·
prompt engineering · function/tool calling · structured output · `RAG` `pgvector` `ChromaDB` ·
**MCP server authoring** · `LangChain` `LangGraph` · `Whisper` · multilingual NLU

**Backend**
`Python` `FastAPI` `Django` `Flask` · `Node.js` `Express` `Fastify` `TypeScript` ·
REST · webhooks · WebSockets · `async SQLAlchemy` `Prisma` `Alembic` · `Redis` `BullMQ` `APScheduler` ·
JWT / NextAuth / bcrypt · role- and permission-based access control

**Frontend & Mobile**
`React` `Next.js` `Vite` `Tailwind CSS` `shadcn/ui` `TanStack Query` `Zustand` `Recharts` ·
`React Native / Expo` · `Kotlin` `Jetpack Compose` `Room` `CameraX`

**Data**
`Pandas` `NumPy` `SciPy` `Parquet` `scikit-learn` `statsmodels` · ETL and reconciliation ·
forensic data audit · `Playwright` `Selenium` · `python-docx` `PyMuPDF` `openpyxl`

**Databases & Infra**
`PostgreSQL` `MongoDB` `SQLite` `MySQL` `Redis` · `Docker` `Linux` `AWS` `Nginx` `GitHub Actions` ·
`pytest` `Vitest` `Jest` `Playwright`

---

## Background

- **AI Engineer** — Cafe Uppercrust Group, Ahmedabad · May 2026 – present
- **Research Analyst (AI & Quantitative Systems)** — Junomoneta Finsol · Jan 2026 – Apr 2026
- **Associate Research Analyst (Data Engineering)** — Junomoneta Finsol · Jul 2025 – Dec 2025
- **B.Tech, Computer Science (Data Science)** — Brainware University, 2025
- NISM Series VIII (Equity & Derivatives) · NSE Academy Certified Financial Markets · Bloomberg Market Concepts

---

## Reach me

- 🌐 **[krishkrkashyap.github.io](https://krishkrkashyap.github.io)** — portfolio and [full résumé](https://krishkrkashyap.github.io/resume.html)
- 💼 [linkedin.com/in/krishkrkashyap](https://www.linkedin.com/in/krishkrkashyap)
- 📧 [krishkrkashyap@gmail.com](mailto:krishkrkashyap@gmail.com)
- 📍 Ahmedabad, Gujarat, India

<sub>Krish Kumar · also known as krishkrkashyap · AI Engineer specialising in applied LLM systems, agent architecture and business automation.</sub>
