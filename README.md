<h1 align="center"><b>Hi, I'm Juan Arena </b> 👋</h1>
<p align="center">
  <b>Business Data Scientist @ Accenture | Python · AI · Machine Learning</b>
  <br>
  <b>Computer Science Student</b>
  <br>
  La Plata, Buenos Aires, Argentina
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/juanignacioarena/">LinkedIn</a> •
  <a href="mailto:juanarena298@gmail.com">Email</a> •
  <a href="https://github.com/Juanarena29">GitHub</a>
</p>

---

## 👨‍💻 About Me

I currently work as a **Business Data Scientist at Accenture**, while finishing my degree in **Computer Science (Lic. en Sistemas)** at **Universidad Nacional de La Plata (UNLP)**.

Outside of work, my personal projects have shifted from classic ML pipelines toward **LLM-based systems**: RAG, agent orchestration, evaluation, and observability. The projects below reflect that progression — from the math underneath transformers, to retrieval pipelines, to agentic systems with tools and guardrails.

---

## 🧰 Technical Skills

**LLMs & Generative AI** — RAG (hybrid search, HyDE, reranking), agent orchestration (OpenAI Agents SDK), LangChain ecosystem, evaluation (RAGAS), observability (LangFuse), embeddings & semantic search

**Machine Learning** — Python (NumPy, pandas, scikit-learn, XGBoost), end-to-end pipelines, feature engineering, model evaluation, neural networks from scratch

**Software Engineering** — Clean Architecture, SOLID, REST APIs, testing (pytest, xUnit)

**Data & Tools** — SQL (PostgreSQL, SQLite), Docker, Git, FastAPI, Streamlit

**Currently learning** — Deep Learning & Transformers, Azure Cloud, metaheuristic optimization (PSO, ACO) for my thesis

---

## 🚀 Featured AI & ML Projects

### 🔎 RAG Platform
`Python · FastAPI · Qdrant · OpenAI · LangFuse · RAGAS`

The most complete project in this list. A full RAG development cycle over technical PDFs: async ingestion, hybrid retrieval (dense + BM25) with query transformation and HyDE, cross-encoder reranking, cited generation, per-step tracing in LangFuse, and quantitative evaluation with RAGAS (25-question eval set, ablation study across retrieval configs).

- Hybrid search + HyDE + reranking pipeline
- LangFuse traces (latency, tokens, cost) per query
- RAGAS evaluation on a fixed 25-question set: **faithfulness 0.86**, **context_recall 1.00**, **answer_relevancy 0.91** — plus a 2×2 ablation isolating the impact of query transformation and HyDE on retrieval quality

🔗 [Repository](https://github.com/Juanarena29/RAG-Platform)

### 🧠 Transformer From Scratch
`Python · NumPy`

An encoder-only Transformer built with NumPy only — no PyTorch, no TensorFlow. The goal was understanding, not speed: manual backpropagation through every layer.

- Custom BPE tokenizer (trained on Spanish)
- Manual backprop (attention, FFN, LayerNorm, cross-entropy)
- Autoregressive generation (greedy / top-k / top-p) + attention visualization

🔗 [Repository](https://github.com/Juanarena29/Transformer-From-Scratch)

### ✈️ BudgetTrip — Agentic Trip Planner
`Python · OpenAI Agents SDK · FastAPI · React`

A learning project exploring the OpenAI Agents SDK: a requirements-gathering chat agent feeds a code-orchestrated pipeline (search planning → execution → itinerary writing) with deterministic budget checks. Includes structured outputs with Pydantic and a Clean Architecture layering.

- Multi-agent pipeline orchestrated by code, not handoffs
- Structured outputs (Pydantic) + iterative fixes for state tracking and date parsing

🔗 [Repository](https://github.com/Juanarena29/BudgetTrip-Agents)

### 🤝 Digital Twin — Conversational Agent
`Python · OpenAI · Gradio · SQLite`

A conversational agent that represents a personal profile on a website, built on the "agent loop + tools" pattern from an agentic AI course, extended with an evaluator, guardrails, and persistent memory.

- 7 tools, generate → evaluate → revise loop (up to 3 retries)
- Guardrails (rate limiting, prompt-injection filtering) + SQLite-backed memory and analytics

🔗 [Repository](https://github.com/Juanarena29/DigitalTwin)

### 📊 ML Workflow Education Tool
`Streamlit · scikit-learn · pandas`

Interactive app guiding users through the full ML lifecycle — ingestion, cleaning, training, evaluation — with built-in guardrails against common mistakes (data leakage, invalid targets).

🔗 [Repository](https://github.com/Juanarena29/ML-WorkFlow-Education-Tool) · [Live demo](https://ml-workflow-education-toolgit-wmxdggenkkoppnwjc2edgy.streamlit.app/)

---

### 📚 Earlier ML projects
- **[House Price Prediction](https://github.com/Juanarena29/House_Price_Prediction--Arena)** — end-to-end pipeline, model comparison via GridSearchCV, R² = 0.95
- **[Neural Network from scratch](https://github.com/Juanarena29/NeuralNetworkv1)** — fully-connected net, manual forward/backprop
- **[BPE Tokenizer](https://github.com/Juanarena29/BPETokenizer)** — custom BPE for Spanish, with demo

### 💻 Software engineering
- **[Rental Management System](https://github.com/Juanarena29/RentalManagementSystem)** — ASP.NET Core 8 / Blazor, Clean Architecture, 66 automated tests
- **[CRUD Blazor App](https://github.com/Juanarena29/CRUD-Blazor-Csharp)** — layered architecture, academic project

---

## 📌 Currently

Working as a **Business Data Scientist at Accenture**. Outside of that, I'm building toward **AI/LLM Engineering** — these projects are where I explore RAG, agents, and evaluation on my own time. Open to conversations about AI engineering, or just talking shop.

## 🎯 Current Focus

- 🔬 Automated Titration Simulator (thesis, UNLP/III-LIDI)
- 🤖 Metaheuristic algorithms (PSO, ACO)
- ☁️ Azure Cloud, Deep Learning & Transformers

## 🤝 Let's Connect

📫 **Email:** juanarena298@gmail.com
🔗 **LinkedIn:** [linkedin.com/in/juanignacioarena](https://www.linkedin.com/in/juanignacioarena/)
💻 **GitHub:** [github.com/Juanarena29](https://github.com/Juanarena29)

---

⭐️ *Open to collaboration on AI/ML and data engineering projects*

