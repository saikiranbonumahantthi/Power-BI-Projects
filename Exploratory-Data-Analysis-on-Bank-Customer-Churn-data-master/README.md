# 🏦 Bank Customer Churn — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Author](https://img.shields.io/badge/Author-saikiranbonumahantthi-blue?style=for-the-badge)

> **Deep-dive EDA on 10,000+ bank customers to uncover the key drivers of churn — geography, product usage, activity level, and demographics.**

---

## 📌 Project Overview

This notebook performs thorough exploratory data analysis on a bank customer churn dataset, identifying the most significant factors that lead customers to leave. Findings provide actionable intelligence for retention teams.

## 💡 Key Findings

| Variable | Churn Insight |
|---|---|
| 🌍 Geography | Germany has the highest churn rate (~32%) — 2x France and Spain |
| 👤 Gender | Female customers churn at 25% vs 16% for males |
| 💳 Num Products | 3-4 product holders churn at 83-100% — a critical warning signal |
| 🔴 Active Member | Inactive members churn at 27% vs 14% for active |
| 💰 Balance | Mid-to-high balance inactive customers are highest risk segment |
| ⏳ Tenure | U-shaped pattern — new (yr 1) and long-term (yr 9+) customers at risk |
| 📊 Credit Score | Scores below 400 show meaningfully higher churn |

## 📁 Project Files

| File | Description |
|---|---|
| Churn_Modelling.csv | Dataset — 10,000 customers, 14 features |
| Bank Churn Modelling.ipynb | Complete EDA notebook with 25+ visualizations |

## 🛠️ Tech Stack

- **Python 3.x** — Core analysis language
- **Pandas** — Data loading, cleaning, aggregation
- **Matplotlib & Seaborn** — Distribution plots, heatmaps, correlation matrix
- **NumPy** — Numerical operations

## 📊 Analysis Sections

1. Data Overview — Shape, dtypes, missing values, duplicates
2. Univariate Analysis — Distribution of each feature
3. Bivariate Analysis — Feature vs Churn rate
4. Multivariate Analysis — Interaction effects between variables
5. Churn Customer Profile — Who is most likely to churn
6. Business Recommendations — Retention strategies

## 👤 Author
**Sai Kiran Bonumahantthi** | [GitHub](https://github.com/saikiranbonumahantthi) | saikiranbonumahanthi1@gmail.com