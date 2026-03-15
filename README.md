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

### Programming & Tools
- **Python** (pandas, NumPy, scikit-learn, matplotlib, pytest)
- **SQL** (SQLite, PostgreSQL)
- **C#** (.NET, Blazor)
- **JAVA**
- **Git & GitHub**

### Data Engineering & Analytics
- ETL pipelines & data transformations
- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering

### Machine Learning
- Supervised learning (Regression, Classification)
- Model comparison & hyperparameter tuning (GridSearchCV)
- Pipeline design (StandardScaler, OneHotEncoder, ColumnTransformer)
- Metrics evaluation (MAE, RMSE, R², overfitting detection)
- Model persistence (joblib)

### Visualization & BI
- Power BI
- Matplotlib, Seaborn, Plotly

### Software Engineering
- SOLID principles
- Modular architecture & clean code
- Test-driven development (pytest, >95% coverage)
- Version control (Git/GitHub)
- Docker containerization

### Currently Learning
- Azure Cloud Services
- IA Engineering
- Advanced ML algorithms (PSO, Genetic Algorithms)

---

## 🚀 Featured Projects

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

### 🧠 Neural Network v1 – Fully-Connected Net from Scratch
**Technologies:** Python, NumPy, scikit-learn, matplotlib

Fully-connected neural network **built from scratch using NumPy only**, with no deep learning libraries. Every mathematical operation derived and implemented explicitly, benchmarked against scikit-learn's LinearRegression.

- **Forward pass** with pre-activations Z, ReLU activations on hidden layers, and linear output for regression
- **Full backpropagation** derived by hand: dZ, dW, db propagated layer by layer via chain rule
- **ReLU derivative** implemented as a binary mask over the gradients
- **Mini-batch gradient descent** with per-epoch shuffle — intentionally implemented to demonstrate its behavior at scale
- **He initialization**, normalization computed exclusively on train set, 70/15/15 split
- **All matrix operations** with explicit shapes documented in the README

**Benchmark vs scikit-learn LinearRegression** — same dataset, same split:

| Model | MAE | RMSE |
|---|---|---|
| **Neural Net (NumPy)** | **9,022** | **11,097** |
| Linear Regression (sklearn) | 8,963 | 10,889 |

🔗 [github.com/Juanarena29/NeuralNetworkv1](https://github.com/Juanarena29/NeuralNetworkv1)

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

- **Junior Data Engineer**  
- **ML Engineer / Data Scientist Jr**  
- **Analytics Engineer**  
- **Data Analyst** (Python/SQL focused)

I'm especially interested in roles where I can work with **ML pipelines, data engineering workflows, and production-ready solutions**.

---

## 🎯 Current Focus

- 🔬 Developing an **Automated Titration Simulator** (thesis project - UNLP/III-LIDI)
- 🤖 Exploring **metaheuristic algorithms** (PSO, Genetic Algorithms, Black Hole Algorithm)
- ☁️ Learning **Azure Cloud** and **Docker**
- 📊 Building **scalable ML pipelines** and **automated workflows**

---

## 🤝 Let's Connect

If you'd like to talk about **data, machine learning, projects, or opportunities**, feel free to reach out!

📫 **Email:** juanarena298@gmail.com  
🔗 **LinkedIn:** [linkedin.com/in/juanignacioarena](https://www.linkedin.com/in/juanignacioarena/)  
💻 **GitHub:** [github.com/Juanarena29](https://github.com/Juanarena29)

---

⭐️ *Open to collaboration on data engineering and ML projects*

