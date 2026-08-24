# Banking_Customer_Analysis
A end-to-end data analytics project that explores a retail/private banking customer dataset through Python-based Exploratory Data Analysis (EDA) and an interactive Power BI dashboard, surfacing insights on customer demographics, wealth distribution, product holdings, and risk profiles.

---

## 📌 Project Overview

This project analyzes a synthetic banking dataset of **3,000 clients** to understand customer segments, financial behavior, and risk exposure. The workflow covers the full analytics pipeline:

1. **Data Cleaning & Exploration** — performed in Python (Pandas, Seaborn, Matplotlib) inside a Jupyter/Colab notebook.
2. **Business Intelligence Reporting** — built as an interactive Power BI (`.pbix`) dashboard for stakeholder-facing insights.

![image alt](https://github.com/dashimanshu369-debug/Banking_Customer_Analysis/blob/36accd09b5d29a48e42abc72ac4f8779b1acb89d/1787142952458.jpg)

![image alt](https://github.com/dashimanshu369-debug/Banking_Customer_Analysis/blob/f26de14dc3d750de51bd6c933439eb7223a40dd5/Screenshot%202026-08-19%20172309.png)

![image alt](https://github.com/dashimanshu369-debug/Banking_Customer_Analysis/blob/cada6a2cd092e85a99a8c8e292c807ca679cc870/Screenshot%202026-08-19%20172442.png)

![image alt](https://github.com/dashimanshu369-debug/Banking_Customer_Analysis/blob/334e7a5e2d93b58835962708501a2f4ca95f1f26/Screenshot%202026-08-19%20172505.png)

---

## 📊 Dataset

**File:** `Banking_case.csv` — 3,000 rows × 24 columns

| Column | Description |
|---|---|
| Client ID | Unique customer identifier |
| Name | Customer name |
| Age | Customer age |
| Location ID | Branch/region identifier |
| Joined Bank | Date the customer joined the bank |
| Banking Contact | Assigned relationship manager |
| Nationality | Customer nationality group |
| Occupation | Customer's job title |
| Fee Structure | Fee tier (e.g., High/Medium/Low) |
| Loyalty Classification | Loyalty tier (e.g., Jade, Gold) |
| Estimated Income | Estimated annual income |
| Superannuation Savings | Retirement/pension savings |
| Amount of Credit Cards | Number of credit cards held |
| Credit Card Balance | Outstanding credit card balance |
| Bank Loans | Outstanding loan balance |
| Bank Deposits | Total deposit balance |
| Checking Accounts | Checking account balance |
| Saving Accounts | Savings account balance |
| Foreign Currency Account | Foreign currency holdings |
| Business Lending | Business loan exposure |
| Properties Owned | Number of properties owned |
| Risk Weighting | Assigned credit/risk score |
| BRId | Business relationship / segment ID (e.g., Retail, Private Bank, Institutional) |
| GenderId | Customer gender |

---

## 🔍 Exploratory Data Analysis (Notebook)

The notebook (`Untitled0.ipynb`) performs:

- **Data profiling** — shape, dtypes, and summary statistics (`df.info()`, `df.describe()`)
- **Feature engineering** — binning `Estimated Income` into **Low / Medium / High** income bands
- **Univariate analysis** — distribution of categorical fields (Business Segment, Gender, Nationality, Occupation, Loyalty Tier, Risk Weighting, Income Band, etc.)
- **Bivariate analysis** — categorical breakdowns segmented by **Gender** and **Nationality**
- **Numerical distribution analysis** — histograms with KDE for income, savings, balances, loans, and deposits
- **Correlation analysis** — a heatmap across all numerical financial variables

### Key Insight
The strongest positive correlations were found between **Bank Deposits** and **Checking Accounts**, **Saving Accounts**, and **Foreign Currency Accounts** — indicating that customers who maintain higher balances in one account type tend to hold substantial funds across other account types as well.

---

## 📈 Power BI Dashboard

**File:** `Banking_Dashboard_2026_.pbix`

An interactive dashboard built on top of the same dataset, designed to give business stakeholders a visual, filterable view of the customer base — including demographic breakdowns, income and deposit distributions, product holdings (loans, credit cards, savings), and risk segmentation. Filters/slicers allow drill-down by segment (Retail, Private Bank, Institutional), nationality, gender, and loyalty tier.

---

## 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| Language | Python 3 |
| Libraries | `pandas`, `numpy`, `matplotlib`, `seaborn` |
| Notebook Environment | Jupyter / Google Colab |
| BI & Visualization | Microsoft Power BI Desktop |

---


## 🙋 Author

**HIMANSHU DAS**
