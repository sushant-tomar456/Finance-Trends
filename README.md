# 📊 Investor Behaviour & Finance Trends (2020–2025)

A dynamic, end-to-end data analytics project exploring investor behaviour and financial trends from 2020 to 2025. Built using Excel, PostgreSQL, Python, and Power BI — covering the full analytics pipeline from raw data to an interactive dashboard.

---

## 2. Purpose

This project analyzes a 12,000-row investment survey dataset to uncover patterns in how people invest, what returns they expect, and what financial goals drive their decisions. The dashboard is designed for finance enthusiasts, data analytics learners, and recruiters who want to see a complete, real-world analytics workflow.

---

## 3. Tech Stack

The project was built using the following tools and technologies:

- 🟢 **Excel (Power Query)** — Initial data exploration, column renaming (snake_case), and sanity checks.
- 🐘 **PostgreSQL** — Data storage using a star schema with 5 tables; SQL queries for aggregations and transformations.
- 🐍 **Python (Pandas, NumPy, Matplotlib, Seaborn)** — Data cleaning, EDA, and visualization of investor trends.
- 📊 **Power BI Desktop** — Star schema data model, DAX measures, KPI cards, and interactive dashboard.
- 🗂️ **File Formats** — `.csv` for raw/cleaned data, `.pbix` / `.pbit` for the dashboard, `.png` for preview.

---

## 4. Data Source

- **Dataset:** Finance Trends 2020–2025 (sourced from Kaggle)
- **Size:** 12,000 rows × 24 columns
- **Domain:** Investment & Financial Behaviour (survey-style data)
- **Missing Values:** None (0 nulls across all columns)

---

## 5. Features / Highlights

**Business Problem:** Financial institutions and analysts often lack visibility into what drives retail investor behaviour — what avenues they prefer, how long they invest, and what returns they expect.

**Goal of the Dashboard:** To deliver an interactive analytics report that reveals demographic and behavioural patterns in investor decision-making — enabling data-driven insights for financial advisors, product teams, and researchers.

**Walkthrough of Key Visuals:**

- **KPI Cards (Top Row):**
  - Total Investors: 12,000
  - Average Age: 27.8
  - Top Investment Avenue: Gold
  - Most Common Duration: 3–5 years
  - Most Expected Return Range: 30%–40%

- **Gender Distribution (Donut Chart):** Male investors make up 62.6% of respondents; female 37.4%.

- **Investment Monitoring Frequency (Bar Chart):** Shows how often investors track their portfolios — Daily, Weekly, or Monthly.

- **Expected Return Range (Bar Chart):** Reveals that 30%–40% is the most commonly expected return range, followed by 10%–20% and 20%–30%.

- **Top Savings Objectives (Treemap):** Retirement Plan dominates, followed by Health Care and Education.

- **Investment Duration (Bar Chart):** 3–5 years is the most preferred investment horizon.

- **Slicers:** Interactive filters for Gender, Duration, and Expected Return Range — allowing dynamic exploration of all visuals.

**Business Impact & Insights:**
- Gold is the top-rated investment avenue — suggesting preference for safe, tangible assets.
- Most investors are young (avg. age 27.8), risk-tolerant, and expecting high returns (30–40%).
- Retirement planning is the dominant savings goal — a key insight for financial product targeting.
- Weekly monitoring is most common — indicating active engagement with investments.

---

## 6. Project Pipeline

| Phase | Tool | Description |
|-------|------|-------------|
| 1. Data Understanding | Excel | Explored structure, columns, data types, and relationships |
| 2. Data Cleaning | Python (Pandas) | Renamed columns to snake_case, handled missing values, standardized text |
| 3. Data Storage | PostgreSQL | Created star schema with 5 tables, imported cleaned CSV |
| 4. Exploratory Analysis | Python (Matplotlib, Seaborn) | Visualized preferences, durations, expected returns, and demographics |
| 5. Dashboard Creation | Power BI | Built interactive dashboard with DAX measures, KPI cards, and slicers |

---

## 7. Star Schema (PostgreSQL)

```
investor_demographics  ──┐
investor_preferences   ──┤
investor_behavior      ──┼──► stg_finance_trends (Staging)
investor_reasons       ──┤
information_source     ──┘
```

---

## 8. Key Problem Statements Answered

1. What is the distribution of investors by gender and age?
2. Which investment avenues are most preferred overall?
3. How do investment preferences vary between genders?
4. What is the preferred investment duration?
5. How often do investors monitor their investments?
6. What rate of returns do investors expect?
7. Is there a relationship between monitoring frequency and expected returns?
8. What are the most common financial goals among investors?
9. Where do investors get their financial knowledge from?
10. What strategies could financial institutions use to target the right audience?

---

## 9. Screenshots / Demo

![Finance Trends Dashboard](https://raw.githubusercontent.com/sushant-tomar456/Finance-Trends/main/Finance%20Trends%202020-2025.png)

---

## 10. Files in This Repository

| File | Description |
|------|-------------|
| `Finance_Trends.csv` | Raw dataset (sourced from Kaggle) |
| `Investor_Behaviour_Finance_Trends_2020_2025.pbit` | Power BI Template file |
| `Finance_Trends_2020-2025.png` | Dashboard screenshot |
| `README.md` | Project documentation |

---

## 11. Tools & Skills Demonstrated

`Data Cleaning` · `Power Query` · `PostgreSQL` · `Star Schema` · `Python` · `Pandas` · `Seaborn` · `Matplotlib` · `EDA` · `Power BI` · `DAX` · `Data Modelling` · `Dashboard Design` · `Storytelling with Data`

---

*Dashboard by Sushant Tomar | MCA Graduate | Aspiring Data Analyst*
