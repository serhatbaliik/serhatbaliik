<div align="center">

<img src="https://raw.githubusercontent.com/serhatbaliik/serhatbaliik/main/Data.png" width="75%"/>

# 👋 Hi, I'm Serhat
### Data Analyst · Financial Analyst · Mathematics

<img src="https://komarev.com/ghpvc/?username=serhatbaliik&color=185FA5&style=flat&label=Profile+Views" alt="profile views"/>

</div>

---

## 🚀 About Me

I'm a **Mathematics graduate** passionate about transforming raw data into **actionable insights** that drive business and financial decisions. My expertise lies in statistical modeling, building analytical pipelines, and creating dashboards that enable data-driven decision-making.

- 📊 **Data Analysis & Reporting** — Python-based EDA, KPI dashboards, automated reporting with Power BI & Excel.
- 📐 **Statistical Modeling** — Hypothesis testing, regression analysis, time series decomposition, Mann-Kendall trend analysis, Moran's I spatial autocorrelation, bootstrap & Monte Carlo simulation, K-Means clustering, LDA, PCA, entropy weighting, network flow optimization.
- 💰 **Financial Analytics** — sales reconciliation, budget tracking, financial performance reporting and dashboard design.
- 🐍 **Python (pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels)** — data cleaning, automation, and advanced visualizations.
- 🗄️ **SQL** — high-performance queries and reproducible analysis workflows.
- 🔬 **Academic Research** — water security risk index modeling, HDI clustering analysis, traffic flow optimization — all presented in academic papers and workshops.

> Currently seeking **Data Analyst** or **Financial Analyst** positions.

---

## 📫 Connect with Me

<div align="center">

| LinkedIn | GitHub | Email |
|:---:|:---:|:---:|
|[<img src="https://raw.githubusercontent.com/serhatbaliik/serhatbaliik/main/lin.png" width="60px">](https://linkedin.com/in/serhatbal%C4%B1k) | [<img src="https://raw.githubusercontent.com/serhatbaliik/serhatbaliik/main/git.png" width="60px">](https://github.com/serhatbaliik) | [<img src="https://raw.githubusercontent.com/serhatbaliik/serhatbaliik/main/mail.png" width="60px">](mailto:serhat_serhatt@outlook.com) |

</div>

---

## 🛠 Data & Analytics Stack

**Languages & Databases**
> Python · SQL · PostgreSQL · MySQL · SQLite

**Data Analysis & Manipulation**
> pandas · NumPy · SciPy · Statsmodels

**Visualization & BI**
> Matplotlib · Seaborn · Plotly · Power BI · Excel · Streamlit

**Statistical Methods**
> Descriptive & Inferential Statistics · Hypothesis Testing · Regression Analysis ·
> Time Series Analysis · Mann-Kendall Trend Test · Moran's I Spatial Autocorrelation ·
> Bootstrap & Monte Carlo Simulation · Entropy Weighting · K-Means Clustering ·
> Linear Discriminant Analysis (LDA) · PCA · A/B Testing · Network Flow Optimization

**Tools & Workflow**
> Git · GitHub · Jupyter · Google Colab · VS Code

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

</div>

---

## 📌 Featured Projects

### 💧 İzmiRisk — Water Security Risk Dashboard
> Faculty-approved academic research project. Streamlit web application analyzing Water Security Risk Index (WSRI) scores across İzmir's 11 central districts (2010–2023).

🌐 **Live App:** [izmirisk.streamlit.app](https://izmirisk.streamlit.app)

- Designed a **composite WSRI** combining 4 key indicators (per capita consumption, population growth rate, supply constraints, water loss rate) using **entropy-based weighting** derived from real İZSU open data
- Extended the real 4-year dataset to a **14-year synthetic time series** (2010–2023) via bootstrap resampling, enabling robust long-term trend analysis
- Applied **Mann-Kendall trend testing** for monotonic trend detection and **Moran's I spatial autocorrelation** for district-level clustering behavior
- Generated **2030 risk projections** under 3 CAGR-based scenarios (Optimistic / Base / Pessimistic) with comparative district-level reporting
- Built an **interactive Streamlit dashboard** with KPI cards, dynamic filters, scenario simulator, and automated CSV export
- Produced district-level policy recommendation reports based on statistical outputs

**Stack:** Python · Streamlit · pandas · NumPy · SciPy · Statsmodels · Plotly · Git

---

### 📊 Sales Performance Dashboard — Excel & Power BI
> Interactive sales analytics dashboard analyzing monthly performance across employees, regions, and product categories.

- Tracked **total revenue, profit margin, and unit sales** with dynamic KPI cards and top performer rankings
- Built **product-based and city-based revenue breakdowns** using bar charts and geographic visualizations
- Designed **employee performance tracking** with monthly trend lines and gender distribution analysis
- Enabled month-by-month drill-down via **pivot tables and interactive slicers**

<div align="center">
  <img src="https://raw.githubusercontent.com/serhatbaliik/serhatbaliik/main/dash.png" width="85%"/>
</div>

**Stack:** Excel (Advanced) · Power BI · Pivot Tables · Data Visualization

---

### 🌍 Linear Discriminant Analysis on Human Development Index
> Mathematics thesis project. Multivariate statistical analysis of 193 UN member states
> using unsupervised clustering and supervised dimensionality reduction.
> *İzmir University of Economics, Dept. of Mathematics — 2024*

- Sourced and preprocessed HDI dataset (193 countries) covering **Life Expectancy Index,
  Education Index, and Income Index** — applied standardization to ensure equal feature
  weighting
- Applied **Elbow Method** to determine optimal cluster count; executed **K-Means
  Clustering** (K=3 and K=4) with fixed random seed for reproducibility
- Validated clustering results using **Linear Discriminant Analysis (LDA)** — maximized
  between-class scatter (S_B) relative to within-class scatter (S_W) via eigenvalue
  decomposition of S_W⁻¹ S_B
- Computed full **covariance matrices**, **projection vectors**, and **transformed
  subspaces** (Y = XW) step by step; verified alignment between LDA-predicted groups
  and predefined HDI categories
- Demonstrated that HDI sub-indices reliably separate development tiers — findings
  support data-driven resource allocation for humanitarian crisis response

**Stack:** R · K-Means Clustering · Linear Discriminant Analysis · Statistical Modeling

📄 [Read the Paper →](https://github.com/serhatbaliik/serhatbaliik/blob/main/hdi_paper.pdf)
---

### 🚦 Dynamic Traffic Flow Optimization Using Network Flow Models
> Academic research presented at a workshop, modeling urban traffic as a directed graph optimization problem.

- Modeled urban intersections as **directed graphs** and applied **network flow theory** to optimize traffic routing
- Evaluated model performance against real-world traffic data through **scenario-based simulations**
- Findings presented at an **academic workshop** with a published poster and paper

**Stack:** Python · NetworkX · NumPy · Matplotlib

📄 [Read the Paper →](https://github.com/serhatbaliik/serhatbaliik/blob/main/traffic_paper.pdf)

---

## 💼 Experience

| Company | Focus Area | Key Deliverables |
|---|---|---|
| Unilever (Algida) | Sales Analytics | Reconciliation, reporting pipelines |
| TNC Group | Financial Analysis | Budget tracking, KPI dashboards |
| Teşvik 360° | Data Processing | Incentive analytics, data workflows |

---

## 🎓 Certifications

### Udemy — 2024

| Certificate | Topic |
|---|---|
| [Python A-Z™: Veri Bilimi ve Machine Learning (50 Saat)](https://www.udemy.com/course-dashboard-redirect/?course_id=2310884) | Python · Data Science · ML |
| [MS Excel: Sıfırdan İleri Seviye Excel Öğren](https://www.udemy.com/course-dashboard-redirect/?course_id=1901106) | Excel · Advanced |
| [Power BI: Sıfırdan Uzmanlığa Veri Analizi ve Görselleştirme](https://www.udemy.com/course-dashboard-redirect/?course_id=4747772) | Power BI · Data Visualization |

---

### Miuul — 2026

| Certificate | Link |
|---|---|
| Oracle SQL Developer | [View Certificate](https://learning.miuul.com/certificates/k5fukyphfw) |
| Querying MS SQL | [View Certificate](https://learning.miuul.com/certificates/kbramowip1) |
| Introduction to Data Science and Artificial Intelligence | [View Certificate](https://learning.miuul.com/certificates/7twh5dygnf) |
| Python Programming for Data Science | [View Certificate](https://learning.miuul.com/certificates/n4wzyyefd5) |

---

### Microfon — 2024

<div align="center">

**Temel Finansal Okuryazarlık ve Yatırım Süreçleri**
Microfon · Haz 2024

[📄 View Certificate](https://raw.githubusercontent.com/serhatbaliik/serhatbaliik/main/mic.pdf)

</div>

---



## 📈 GitHub Stats

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=serhatbaliik&show_icons=true&theme=default&hide_border=true&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=serhatbaliik&layout=compact&theme=default&hide_border=true" />
</div>

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=serhatbaliik&theme=flat&no-frame=true&no-bg=true&margin-w=4&column=4" />
</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1D9E75,100:185FA5&height=100&section=footer" width="100%"/>
</div>
