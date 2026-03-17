<h1 align="center"><b>Hi, I'm Juan Arena </b> 👋</h1>
<p align="center">
  <b>ML & IA enthusiast | Python · SQL · Machine Learning</b> 
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

I am a **ML & AI Engineer Jr** in training, currently pursuing my degree in **Computer Science (Lic. en Sistemas)** at **Universidad Nacional de La Plata (UNLP)**.

I work with **Python and SQL** to build **machine learning pipelines**, develop **predictive models**, and create **data-driven solutions**. I have hands-on experience with **end-to-end ML workflows**, designing **modular architectures**, implementing **automated testing**, and applying **software engineering best practices** to ensure scalable and maintainable code.

My goal is to join a team as a **Junior Data Engineer, ML Engineer, or IA Engineer**, where I can contribute with reliable data solutions, production-ready ML models, and continue growing professionally.

---

## 🧰 Technical Skills

### Machine Learning & AI
- Python (NumPy, pandas, scikit-learn, XGBoost)
- End-to-end ML pipelines (data ingestion → preprocessing → training → evaluation → prediction)
- Supervised learning (regression, classification)
- Feature engineering & data preprocessing
- Cross-validation, hyperparameter tuning (GridSearchCV)
- Model evaluation (MAE, RMSE, R², overfitting detection)
- Model serialization & reproducibility (joblib)
- Neural networks from scratch (NumPy implementation, forward/backprop)

### Data Engineering for ML
- Data cleaning and transformation pipelines
- Exploratory Data Analysis (EDA)
- Feature pipelines with ColumnTransformer
- Dataset splitting and leakage prevention
- ETL workflows for ML experimentation

### LLMs & Generative AI
- Retrieval-Augmented Generation (RAG)
- Embeddings and semantic search
- Fine-tuning with QLoRA
- LLM orchestration with LangChain

### Software Engineering
- Object-Oriented Programming (OOP)
- Clean Architecture
- SOLID principles
- Dependency Injection
- Repository & Unit of Work patterns
- Modular system design
- Testing-driven development

### Testing & Reliability
- Automated testing (pytest, xUnit, Moq, FluentAssertions)
- Unit and integration tests
- High test coverage (>80–95%)
- Validation and guardrails for ML pipelines

### Data & Backend Technologies
- SQL (PostgreSQL, SQLite)
- REST APIs
- ASP.NET Core
- Entity Framework Core

### Dev Tools
- Git & GitHub
- Docker
- Streamlit
- Power BI
- Matplotlib, Plotly

### Currently Learning
- Deep Learning & neural network architectures
- Transformers and LLM systems
- Azure Cloud
- Metaheuristic optimization (PSO, Genetic Algorithms)
  
---

# 🚀 Featured Projects

## 🤖 Mini Transformer from Scratch (Work in Progress)
**Technologies**: Python, NumPy

End-to-end implementation of a Transformer architecture built entirely from scratch, focusing on deep understanding of every component without relying on high-level libraries.

This project is structured as a collection of independent sub-projects, each one covering a key building block of modern NLP systems:
## 
### 🔤 BPE Tokenizer – From Scratch

Custom implementation of **Byte Pair Encoding (BPE)** for subword tokenization, built step by step to understand how raw text is transformed into model-ready tokens.

- Character-level initialization with explicit **end-of-word (</w>) handling**
- Iterative **frequency-based pair merging** to build the vocabulary
- Deterministic merge rules applied consistently during encoding

🔗 [https://github.com/Juanarena29/BPE-Tokenizer](https://github.com/Juanarena29/BPETokenizer)

🔗 **DEMO**: https://bpetokenizer-v1.streamlit.app/

## 🧠 Neural Network v1 – NumPy Only

Fully-connected neural network implemented from scratch using **NumPy only**, with all mathematical operations explicitly derived and coded.

- Manual **forward pass** with ReLU activations and linear output
- Full **backpropagation implementation** using the chain rule (dZ, dW, db)
- **Mini-batch gradient descent** with proper data shuffling
- Careful handling of **initialization and data normalization**

🔗 https://github.com/Juanarena29/NeuralNetworkv1

---

### 🎓 ML Workflow – Educational Machine Learning Tool  
**Technologies:** Python, Streamlit, scikit-learn, pandas, NumPy, Plotly, joblib  

Educational web application that **guides users step by step through the complete Machine Learning workflow**, from data ingestion to model prediction and evaluation.

- **Hybrid educational / tooling design**, featuring:
  - **Learn mode**: guided explanations of each ML stage
  - **Tool mode**: hands-on, practical usage for real datasets
- **Explicit project state management**, tracking:
  - original dataset
  - data cleaning steps
  - target selection
  - problem type
  - trained models
- **Built-in validations and guardrails** at each stage to prevent common ML mistakes  
  (invalid target selection, data leakage, inconsistent datasets, etc.).
- **Guided data cleaning configuration**, combining automatic suggestions with full user control.
- **Support for regression and classification problems**, including:
  - appropriate metrics
  - interpretable visualizations
  - error analysis
- **Prediction on new data**, with prediction vs. ground truth comparison when the target is available.
- **Modular and extensible architecture**, prioritizing clarity, reproducibility, and ML best practices over opaque automation.

🔗 **Live Demo:**  
https://ml-workflow-education-toolgit-wmxdggenkkoppnwjc2edgy.streamlit.app/

🔗 **Source Code:**  
https://github.com/Juanarena29/ML-WorkFlow-Education-Tool

---

### 🏨 Rental Management System – Tourist Complex  
**Technologies:** C#, ASP.NET Core 8, Blazor Server, EF Core 8, SQL Server (Azure), xUnit, Moq, FluentAssertions

Custom-built web application developed **to client specifications** for a real 7-apartment tourist complex in Las Grutas, Río Negro. Replaces manual booking logs, WhatsApp notes and spreadsheets with a fully centralized management system.

- **Clean Architecture** across 4 layers (Domain, Application, Infrastructure, Web) with strict dependency rules — Domain has zero external dependencies
- **29 independent Use Cases**, each encapsulating a single business operation for maximum testability and maintainability
- **Overlap detection** — prevents double-booking with composite index-backed queries
- **ACID payment transactions** using Unit of Work pattern, with rollback verified by automated tests
- **Security-first authentication**: PBKDF2 SHA-256 (100k iterations), timing-safe password comparison, anti user-enumeration design
- **Occupancy statistics**: occupancy rate, daily revenue, check-in/check-out dashboard
- **Automated testing** with xUnit + Moq + FluentAssertions — 66 tests covering critical use cases including transaction rollback and security edge cases
- **Production database**: Azure SQL Server — switchable to SQLite locally via single config line

🔗 [github.com/Juanarena29/RentalManagementSystem](https://github.com/Juanarena29/RentalManagementSystem)

---

### 🏠 House Price Prediction – ML Pipeline  
**Technologies:** Python, scikit-learn, pandas, NumPy, matplotlib, pytest, joblib

- Modular **end-to-end ML pipeline** for house price prediction
- **Model comparison** (Random Forest, Gradient Boosting, Decision Tree, Linear Regression) with GridSearchCV
- **Automated testing** with >95% coverage using pytest (AAA pattern)
- **Professional notebooks** with EDA and technical reporting
- Pipeline design with **reproducibility** and **production-ready** architecture

**Results:** R² = 0.95 | MAE < 5% 

🔗 [github.com/Juanarena29/House_Price_Prediction--Arena](https://github.com/Juanarena29/House_Price_Prediction--Arena)

---

### 💼 CRUD Blazor Application – User Management  
**Technologies:** .NET, C#, Blazor, SQLite

- Full-stack CRUD application for user administration (academic group project)
- **Clean architecture** with separation of concerns (Presentation, Application, Domain, Data)
- **Object-oriented design** following SOLID principles
- SQLite database integration with **data validation layer**
- Modular and maintainable codebase

🔗 [github.com/Juanarena29/CRUD-Blazor-Csharp](https://github.com/Juanarena29/CRUD-Blazor-Csharp)

---

## 📌 What I'm Looking For

- **AI Engineer Jr**
- **ML Engineer Jr**
- **Data Engineer Jr**

I'm especially interested in roles where I can work with **ML pipelines, data engineering workflows, and production-ready solutions**.

---

## 🎯 Current Focus

- 🔬 Developing an **Automated Titration Simulator** (thesis project - UNLP/III-LIDI)
- 🤖 Exploring **metaheuristic algorithms** (PSO, ACO)
- ☁️ Learning **Azure Cloud** and **LLM's & DeepLearning**
- 📊 Building **scalable ML pipelines** and **automated workflows**

---

## 🤝 Let's Connect

If you'd like to talk about **data, machine learning, projects, or opportunities**, feel free to reach out!

📫 **Email:** juanarena298@gmail.com  
🔗 **LinkedIn:** [linkedin.com/in/juanignacioarena](https://www.linkedin.com/in/juanignacioarena/)  
💻 **GitHub:** [github.com/Juanarena29](https://github.com/Juanarena29)

---

⭐️ *Open to collaboration on data engineering and ML projects*

