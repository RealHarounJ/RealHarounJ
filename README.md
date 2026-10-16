<div align="center">

# Haroun Jaafar

### Digital Economics & Quantitative Analytics | Software Engineering Background

*BSc in Digital Economics and Business (100% English Taught) · Università Politecnica delle Marche (UNIVPM)*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/haroun-jaafar)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harounjaafar3@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RealHarounJ)

</div>

---

## 👨‍💻 About Me

Undergraduate in **Digital Economics and Business** at Università Politecnica delle Marche (curriculum delivered entirely in English) with a solid software engineering and IT foundation. I specialize in bridging quantitative financial economics, corporate finance, and modern data architectures.

- 🎓 **BSc Digital Economics & Business** @ UNIVPM Ancona (Expected 2027 · Instruction: 100% English)
- 💾 **IT & Telecommunications Diploma** @ ITI Enrico Mattei (Software Engineering, Relational DBs & Networking)
- ⚙️ **Data & Quant Engineering:** Developing automated ETL data pipelines, PostgreSQL warehouses, and Apache Airflow workflows
- 📊 **Quantitative Modeling:** Portfolio optimization (Markowitz), Monte Carlo simulations (GBM), and econometric analysis in R & Python
- 💼 **Former Software & IT Engineering Intern** @ Casali Computers (Enterprise ERP modules & Apache Tomcat deployment)
- 🌍 **International Traineeship:** Seeking Erasmus+ / international quant & data analytics traineeship opportunities for 2026/2027

---

## 🛠️ Technical Stack & Tooling

<div align="left">

**Programming & Scripting**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

**Data Engineering & DevOps**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=flat-square&logo=apache-tomcat&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Quantitative, Scientific & Financial Modeling**  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Tidyverse](https://img.shields.io/badge/Tidyverse-1A1A1A?style=flat-square&logo=r&logoColor=white)
![MetaTrader 5](https://img.shields.io/badge/MetaTrader_5-1B4F72?style=flat-square&logo=metatrader&logoColor=white)

</div>

---

## 🚀 Featured Engineering & Quantitative Projects

### ⚡ [Quant Data Pipeline & Portfolio Optimization Engine](https://github.com/RealHarounJ/quant-data-pipeline)
> **Production-grade automated quantitative ETL, risk forecasting, and portfolio allocation platform**

- **Automated Data Ingestion:** Architected streaming pipelines using `yfinance` to ingest market data into PostgreSQL via idempotent `UPSERT` (`ON CONFLICT`) operations, ensuring data integrity with zero duplicates.
- **Quantitative Optimization & Risk:** Solved Markowitz Mean-Variance portfolio optimization via `scipy.optimize` to calculate Maximum Sharpe Ratio weights; developed a 10,000-path Monte Carlo Geometric Brownian Motion (GBM) engine for 95% Value-at-Risk (VaR) and drawdown forecasting.
- **DevOps & Workflow Orchestration:** Fully containerized with Docker Compose; scheduled sequential execution (`DB Init → Ingest → Optimize → Simulate → Report`) via Apache Airflow DAGs.

`Python` `SQL` `PostgreSQL` `Apache Airflow` `Docker Compose` `Quantitative Finance` `Risk Management`

---

### 🏥 [Clinical Telemetry, Early Warning & Health Economics in R](https://github.com/RealHarounJ/philips-healthtech-clinical-analytics-r)
> **Clinical biosignal telemetry, predictive deterioration modeling, and Health Technology Assessment (HTA) in R**

- **Predictive Clinical Deterioration (AUC = 0.902):** Implemented predictive analytics and Kaplan-Meier survival models to anticipate clinical crises and septic shock prior to standard NEWS2 benchmarks.
- **Decision Curve Analysis (DCA):** Statistical evaluation to mitigate alarm fatigue across hospital departments.
- **Biosignal DSP:** Digital filtering of 100 Hz PPG signals and spectral FFT analysis for Heart Rate Variability (HRV) estimation.
- **Markov Decision Model (HTA):** 1,000 Monte Carlo iterations demonstrating continuous monitoring reduces ICU stays by 1.88 days, yielding >€4,000 cost savings per patient.

`R (tidyverse, survival)` `Biostatistics` `Digital Signal Processing` `Health Economics (HEOR)` `Connected Care`

---

### 🏆 [AFML Quantitative Trading Engine](https://github.com/RealHarounJ/afml-prop-trader)
> **Autonomous algorithmic trading framework incorporating Marcos López de Prado's *Advances in Financial Machine Learning***

- **Fractional Differentiation:** Achieved stationary time-series while preserving maximum memory (AFML Ch. 5).
- **Lempel-Ziv Entropy:** Non-parametric market regime classification (Trend vs. Mean Reversion).
- **Multi-Horizon Trend Scoring & Risk Controls:** Triple-Barrier labeling (TP 4×ATR / SL 2.5×ATR), Winsorization against tail-risk events, and microstructural spread volatility filters.

`Python` `MetaTrader 5` `NumPy` `SciPy` `Algorithmic Trading` `Quantitative Finance`

---

### 🗄️ [Financial Relational Database & Systems Architecture](https://github.com/RealHarounJ/financial-db-design)
> **Relational database design, financial entity modeling, and performance-tuned SQL architectures**

- Engineered normalized ER schemas for financial transactions, billing systems, and enterprise accounting records.
- Authoring high-performance SQL: Window Functions, Common Table Expressions (CTEs), indexing strategies, and query execution plan optimization.

`SQL` `PostgreSQL` `Database Design` `Relational Modeling` `Data Warehousing`

---

## 💼 Commercial & Freelance Analytics Solutions
> *Bridging academic financial rigor and software engineering to generate direct, measurable business ROI.*

- **📊 Automated Financial & Working Capital Dashboards:** Designing end-to-end data pipelines and interactive reporting (R / Python) that eliminate manual spreadsheet reconciliations, track Operating Working Capital (OWC), and calculate real-time net margins.
- **📈 Econometric & Predictive Inference:** Multiple linear regression, sales elasticity, and customer retention/churn analytics (RFM) to quantify revenue drivers with statistical rigor (hypothesis testing, confidence intervals).
- **🗄️ Financial Data Normalization & ETL Pipelines:** Cleaning, standardizing, and restructuring multi-source transactional databases (PostgreSQL, ERP exports) for audit-ready managerial reporting.

---

## 📖 Current Academic & Research Curriculum

```
📚 Currently Focusing On:
   ├── Corporate Finance & Financial Economics (UNIVPM)
   ├── Applied Econometrics & Statistical Computing (R / Python)
   ├── Business Information Systems & Data Mining (SQL, Data Warehouses)
   └── Planning & Control Systems (Management Accounting & KPIs)

🔜 Advanced Roadmap:
   ├── Options Pricing Models (Black-Scholes, Stochastic Volatility)
   ├── Multi-Factor Risk Pricing (Fama-French 5-Factor Model)
   └── CFA Level 1 Preparation
```

---

## 📈 GitHub Metrics

<div align="center">

[![Haroun's GitHub Stats](https://github-readme-stats.vercel.app/api?username=RealHarounJ&show_icons=true&theme=dark&hide_border=true&count_private=true)](https://github.com/RealHarounJ)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=RealHarounJ&layout=compact&theme=dark&hide_border=true)](https://github.com/RealHarounJ)

</div>

---

## 📫 Connect with Me

- 💼 **LinkedIn:** [linkedin.com/in/haroun-jaafar](https://linkedin.com/in/haroun-jaafar)
- 📧 **Personal Email:** [harounjaafar3@gmail.com](mailto:harounjaafar3@gmail.com)
- 🎓 **University Email:** [haroun.jaafar@studenti.univpm.it](mailto:haroun.jaafar@studenti.univpm.it)
- 🌍 **Availability:** Open for High-Impact Freelance Analytics Projects & International Traineeships (Netherlands / EU 2026/2027)

---

<div align="center">
<i>"The goal of all models is to simplify reality enough to make decisions, but not so much that the decisions are wrong." — Marcos López de Prado</i>
</div>
