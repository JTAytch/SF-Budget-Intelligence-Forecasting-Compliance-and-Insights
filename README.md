# 💰 SF Budget Intelligence: Forecasting, Compliance, and Insights

**Author:** Joseph Tulani Aytch  
**Dataset:** [San Francisco Budget Data](https://data.sfgov.org/City-Management-and-Ethics/Budget/xdgd-c79v/about_data)

---

## 📌 Project Overview
This project explores San Francisco’s public budget data to answer key questions:
- How do budgeted vs. actual expenditures vary across departments and years?
- Which departments consistently overspend or underspend?
- Can we forecast future budget needs and identify compliance risks?
- How can stakeholders interact with these insights through dashboards and apps?

The project demonstrates an **end-to-end workflow**: SQL data modeling, Python EDA, R statistical testing, machine learning forecasting, and BI storytelling.

---

## 🎯 Objectives
- Build a **SQL star schema** for budget data and write analytical queries.
- Conduct **exploratory analysis** in Python to uncover trends and anomalies.
- Use **R** for hypothesis testing and statistical validation of spending patterns.
- Develop **forecasting models** (Prophet/ARIMA/XGBoost) for budget projections.
- Create **dashboards and an interactive app** for stakeholders.
- Deliver a polished, recruiter-friendly portfolio project.

---

## 🛠 Tech Stack
- **Languages:** Python, SQL, R  
- **Libraries:** pandas, seaborn, matplotlib, scikit-learn, statsmodels, Prophet, tidyverse  
- **Databases:** PostgreSQL / SQLite  
- **Visualization:** Tableau, Power BI, Streamlit  
- **Other:** GitHub for version control, RMarkdown for reporting

---

## 📂 Project Structure
```text
SF-Budget-Intelligence/
├── data/                # Raw and cleaned datasets
├── sql/                 # Schema and analytical queries
│   ├── schema.sql
│   ├── variance_queries.sql
│   └── trend_analysis.sql
├── notebooks/
│   ├── 01_sql_exploration.ipynb
│   ├── 02_python_eda.ipynb
│   ├── 03_forecasting.ipynb
│   └── 04_r_analysis.Rmd
├── app/                 # Streamlit app
│   └── app.py
├── dashboard/           # Tableau/Power BI files
├── reports/             # RMarkdown reports, visuals
├── requirements.txt
└── README.md
```

---

## 🔍 Methods

### 1. SQL Data Modeling & Cleaning
- Designed a star schema with `fact_budget` and supporting dimension tables (`dim_department`, `dim_date`).
- Wrote SQL queries for:
  - Budget vs. actual variance
  - Year‑over‑year growth
  - Compliance KPIs (departments within ±5% of budget)

### 2. Python EDA
- Loaded cleaned data into pandas for exploration.
- Visualized budget vs. actual trends by department and fiscal year.
- Highlighted outliers and anomalies with seaborn/matplotlib plots.

### 3. R Statistical Analysis
- Conducted hypothesis testing (t‑tests, ANOVA) on spending patterns.
- Built confidence intervals for variance across years.
- Used survival/inference techniques to analyze persistence of overspending.

### 4. Machine Learning / Forecasting
- Built time series forecasts (Prophet/ARIMA) for department budgets.
- Trained classification models (Logistic Regression, XGBoost) to predict overspending risk.
- Evaluated models with accuracy, recall, RMSE, and PR‑AUC.

### 5. Visualization & Storytelling
- Developed Tableau/Power BI dashboards for executive‑level reporting.
- Built a Streamlit app for interactive “what‑if” budget scenarios.
- Created RMarkdown reports for statistical summaries.

---

## 📈 Results (to be filled in)
- Key insights from SQL queries
- EDA highlights
- Forecasting accuracy metrics
- Dashboard screenshots

---

## 🚀 Next Steps
- Expand forecasting models with external drivers (e.g., inflation, population).
- Enhance Streamlit app with department‑level drilldowns.
- Automate ETL pipeline for continuous updates.

---

## 📬 Contact
For questions or collaboration:  
- **LinkedIn:** [Joseph Tulani Aytch](https://www.linkedin.com/in/josephtulaniaytch)  
- **Email:** tulan94@gmail.com

---

## ✅ Project Progress Tracker

- [x] **Day 1–2:** Project setup & initial data ingestion  
  - Created GitHub repo and README skeleton  
  - Downloaded SF Budget dataset  
  - Ran initial SQL checks (row counts, nulls, duplicates)

- [ ] **Day 3–4:** SQL data modeling & cleaning  
  - Design star schema (fact + dimensions)  
  - Write queries for variance, YOY growth, compliance KPIs  

- [ ] **Day 5–6:** Python EDA  
  - Load cleaned data into pandas  
  - Visualize budget vs actual trends  
  - Identify anomalies and outliers  

- [ ] **Day 7–8:** R statistical analysis  
  - Run hypothesis tests (t‑tests, ANOVA)  
  - Build confidence intervals for variance  
  - Document results in RMarkdown  

- [ ] **Day 9–10:** Machine learning / forecasting  
  - Build baseline time series forecast (Prophet/ARIMA)  
  - Train overspend classifier (Logistic Regression/XGBoost)  
  - Evaluate with accuracy, recall, RMSE  

- [ ] **Day 11–12:** Visualization & app  
  - Tableau/Power BI dashboard with KPIs and forecasts  
  - Streamlit app for “what‑if” budget scenarios  

- [ ] **Day 13:** Documentation & polish  
  - Fill in README results and visuals  
  - Add screenshots of dashboards and plots  

- [ ] **Day 14:** Portfolio integration  
  - Draft resume bullets  
  - Write LinkedIn post  
  - Final repo cleanup (requirements.txt, SQL scripts, RMarkdown)

