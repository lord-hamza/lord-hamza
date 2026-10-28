<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="Muhammad Hamza, AI Engineer and Python Backend Engineer">
</p>

<p align="center">
  <a href="mailto:hamzashahbaz5703@gmail.com"><img src="https://img.shields.io/badge/Email-hamzashahbaz5703%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Based%20in-London%2C%20UK-131C3A?style=flat-square" alt="Based in London, UK">
  <img src="https://img.shields.io/badge/Python-7%2B%20years-3776AB?style=flat-square&logo=python&logoColor=white" alt="7+ years of Python">
  <img src="https://img.shields.io/badge/Clients-US%20%C2%B7%20Canada%20%C2%B7%20EU-6366F1?style=flat-square" alt="Clients in the US, Canada and the EU">
</p>

### 👋 About me

I'm an AI engineer with 7+ years of Python behind me. Right now I lead an AI team at **Live Chat Global**, where we build a multi-tenant customer support platform that answers across chat, email and other channels using Claude, OpenAI and Pinecone. I also led a computer vision product that spots vehicle damage with YOLO and turns it into an itemized repair estimate.

I came to AI from backend work. I spent years building APIs in FastAPI and Django, so I care about the boring parts that keep AI features alive in production: retries, timeouts, tenant isolation, validation and cost. I still write most of the hard code myself.

### 🧠 What I focus on

**AI and machine learning (main focus)**

- **LLM systems in production:** multi-model consensus, provider failover, response validation, structured outputs and token budgets
- **RAG and search:** Pinecone and pgvector, hybrid keyword plus vector search, reranking and answers with citations
- **Evaluation and guardrails:** golden question sets, retrieval and answer quality metrics in CI, PII redaction and prompt-injection defence
- **Agentic AI:** tool use over MCP, multi-step agent flows plus voice and chat agents built with Vapi, Deepgram and ElevenLabs
- **Computer vision and OCR:** YOLO detection and training pipelines, OpenCV, PaddleOCR and EasyOCR, face verification
- **Classical ML:** PyTorch, TensorFlow, scikit-learn and Hugging Face models for prediction and classification

**Backend engineering (the foundation)**

- Multi-tenant APIs in FastAPI and Django with JWT and OAuth 2.0, RBAC, webhooks and rate limiting
- PostgreSQL schema design, indexing and query tuning, plus Redis caching and Celery background jobs
- Data pipelines: scraping, enrichment and processing datasets with millions of rows, with BigQuery when it helps
- Docker, CI/CD and cloud deployments on AWS, GCP and Azure

### 💼 Current role

**Team Lead, AI Engineering at Live Chat Global** · Oct 2024 to present · Remote

- Architected an **AI Autopilot** across 4 support channels, grounded in 11 knowledge-base integrations (Python 3.12, FastAPI, the Claude and OpenAI APIs, Pinecone)
- Designed **multi-model consensus answering**, where Claude and OpenAI responses are cross-checked before delivery to cut hallucinations. It's built without LangChain or LlamaIndex for full control and no vendor lock-in.
- Built a **multi-tenant RAG layer** with Pinecone namespaces, org-scoped retrieval and JWT auth so every tenant's data stays isolated
- Built a **resilient LLM service layer** with failover, response validation and token optimization that keeps cost per conversation predictable under flat pricing
- Led a **vehicle damage inspection platform:** a YOLO detection microservice on FastAPI, a React Native capture app and a Next.js review dashboard, trained through a three-phase pipeline with tuned augmentation and regularization
- Built **repair cost estimation** with GPT-4o and Pinecone RAG over repair pricing data, turning detected damage into itemized estimates
- Architected the core **Python backend** for the unified communications platform across phone, email and web, built for high volume and SOC 2 compliance
- Wrote the PRD, technical implementation guide, AI model specification and 90-day delivery plan. I run sprint planning and code reviews for a cross-functional team.

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/lord-hamza/gatewise"><img src="https://raw.githubusercontent.com/lord-hamza/gatewise/main/docs/banner.svg" alt="gatewise"></a>

**[gatewise](https://github.com/lord-hamza/gatewise)** is an async Python LLM gateway in front of OpenAI, Anthropic and any OpenAI-compatible server.

- Failover with jittered backoff that honours `Retry-After`, with timeouts per attempt and per stream chunk
- Semantic cache scoped per tenant and per conversation, plus per-tenant token budgets
- PII redaction, prompt-injection detection and Pydantic-validated outputs with automatic repair
- Only httpx and pydantic at runtime, 113 tests and `mypy --strict`

</td>
<td width="50%" valign="top">

<a href="https://github.com/lord-hamza/pgcite"><img src="https://raw.githubusercontent.com/lord-hamza/pgcite/main/docs/banner.svg" alt="pgcite"></a>

**[pgcite](https://github.com/lord-hamza/pgcite)** answers questions over your documents and shows where every answer came from, all on PostgreSQL with pgvector.

- BM25 written in SQL plus pgvector HNSW, merged with Reciprocal Rank Fusion
- A local cross-encoder reranker on CPU and inline `[n]` citations from an extractive or Anthropic backend
- A CI quality gate on 40 golden questions and 5 metrics: recall@5 **0.963** and MRR **0.872**
- FastAPI service that logs latency per stage, tokens and cost in Postgres

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**[RepoGraph](https://github.com/lord-hamza/repograph)** is a TypeScript CLI that turns any repository into a graph of files, functions and classes. From that graph it builds an interactive code atlas, a learning roadmap, an AI pipeline security audit and MCP context with a real MCP server so AI assistants can understand the codebase. It runs fully offline.

</td>
</tr>
</table>

### 🛠️ Tech stack

**AI, ML and LLMs**

<img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,opencv" alt="Python, PyTorch, TensorFlow, scikit-learn, OpenCV">

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square) ![Anthropic Claude](https://img.shields.io/badge/Anthropic%20Claude-191919?style=flat-square&logo=anthropic&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white) ![LlamaIndex](https://img.shields.io/badge/LlamaIndex-8B5CF6?style=flat-square) ![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white) ![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat-square&logo=ultralytics&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-232F3E?style=flat-square) ![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=flat-square) ![AbacusAI](https://img.shields.io/badge/AbacusAI-4B5563?style=flat-square) ![PaddleOCR](https://img.shields.io/badge/PaddleOCR%20%C2%B7%20EasyOCR-4B5563?style=flat-square)

**Voice, agents and automation**

![Vapi](https://img.shields.io/badge/Vapi-5B21B6?style=flat-square) ![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=flat-square&logo=deepgram&logoColor=black) ![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white) ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square) ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=flat-square)

**Backend and APIs**

<img src="https://skillicons.dev/icons?i=fastapi,django,flask,nodejs" alt="FastAPI, Django, Flask, Node.js">

![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) ![Django REST Framework](https://img.shields.io/badge/Django%20REST%20Framework-A30000?style=flat-square) ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white) ![JWT / OAuth 2.0](https://img.shields.io/badge/JWT%20%2F%20OAuth%202.0-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

**Data**

<img src="https://skillicons.dev/icons?i=postgres,redis,mongodb,mysql,sqlite,selenium" alt="PostgreSQL, Redis, MongoDB, MySQL, SQLite, Selenium">

![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square) ![Scrapy](https://img.shields.io/badge/Scrapy-60A839?style=flat-square&logo=scrapy&logoColor=white) ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4B5563?style=flat-square)

**Cloud, DevOps and testing**

<img src="https://skillicons.dev/icons?i=aws,gcp,azure,docker,kubernetes,githubactions,linux,git,postman,jest" alt="AWS, GCP, Azure, Docker, Kubernetes, GitHub Actions, Linux, Git, Postman, Jest">

![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white) ![ClickUp](https://img.shields.io/badge/ClickUp-7B68EE?style=flat-square&logo=clickup&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat-square)

### 🤝 How I work

- **Agile delivery:** I plan sprints, break work into tickets in Jira or ClickUp and keep the team shipping in small steady increments
- **Product thinking:** I write PRDs, technical implementation guides, AI model specs and delivery plans before the first line of code
- **Leading engineers:** I review code, mentor juniors on Python and AI integration patterns and stay hands-on in the codebase myself
- **Working with clients:** I've delivered for clients in the US, Canada and the EU, so I'm used to async communication across time zones
- **Ownership:** I like owning a system end to end, from architecture and deployment to monitoring and iteration

### 📫 Get in touch

The easiest way to reach me is [hamzashahbaz5703@gmail.com](mailto:hamzashahbaz5703@gmail.com). I'm always happy to talk about LLM systems, RAG, agents and the backends that keep them running.
