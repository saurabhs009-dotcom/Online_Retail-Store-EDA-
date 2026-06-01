# 🛒 Online Retail Store — Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.10-blue) ![Pandas](https://img.shields.io/badge/Pandas-EDA-green) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualisation-orange) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

This project performs an end-to-end **Exploratory Data Analysis (EDA)** on the UCI Online Retail Dataset — a real-world transactional dataset from a UK-based online giftware wholesaler. The goal is to uncover sales trends, customer behaviour patterns, and product performance insights that support data-driven business decisions.

---

## 📂 Dataset

- **Source:** [UCI Machine Learning Repository — Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- **Period:** December 2010 – December 2011
- **Records:** ~541,000 transactions
- **Columns:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical plotting |
| Jupyter Notebook | Interactive analysis environment |

---

## 🔍 Analysis Workflow

1. **Data Loading** — Load dataset from Excel file
2. **Data Understanding** — Explore shape, columns, data types, missing values
3. **Data Cleaning** — Handle nulls, duplicates, cancelled orders, invalid entries
4. **Feature Engineering** — Create Sales column, extract Month and Day
5. **Statistical Analysis** — Descriptive stats, business KPIs
6. **Data Visualisation** — Monthly trends, daily patterns, top products, countries, customers
7. **Correlation Heatmap** — Relationships between key numerical variables
8. **Business Recommendations** — Actionable insights for the business

---

## 📊 Key Findings

- 📅 **November is the peak sales month** — driven by pre-Christmas demand
- 🇬🇧 **UK dominates revenue**, but Netherlands, Germany, and EIRE are strong international markets
- 👥 **Top 10% of customers generate ~80% of revenue** — classic Pareto pattern
- 📦 **Small decorative gift items** are the top sellers by volume
- 📆 **Thursday & Tuesday** generate the highest weekday revenue; Sunday is near zero (B2B model)
- 🔗 **UnitPrice has weak correlation with Quantity** — pricing changes may not affect order volumes significantly

---

## 💡 Business Recommendations

1. Launch Q4 inventory and promotional campaigns to capture peak November demand
2. Implement a loyalty programme targeting the top 20% high-value customers
3. Invest in marketing for Netherlands and Germany — the strongest export markets
4. Test value-based pricing strategies since customers show low price sensitivity on quantity

---

