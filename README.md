# 🏦 Banking Analysis Dashboard | Power BI + SQL + Python

### 📊 End-to-End Financial Analytics Project

This project presents a comprehensive **Banking Analytics Dashboard** built using **Power BI**, with additional backend analysis using **SQL and Python (Jupyter Notebook)**.  
The dashboard provides deep insights into banking performance including loan-distribution trends, deposit allocation, customer segmentation and business lending analysis.

---

## 🚀 Project Objective
To analyze key financial indicators and customer trends for a banking institution and derive actionable insights for business decisions and growth strategies.

---

## 🧠 Key Features
- KPI summary covering loans, deposits, savings, and customer metrics
- Interactive filters: Year, Gender, Branch Category, Income Band, Advisor
- Loan and Deposit trend visual analytics by year
- Segmentation by Nationality & BRId (Branch relation)
- Loan-to-Deposit Ratio for financial risk benchmarking
- YOY performance growth for strategic forecasting

---

## 📈 Key Insights
| Insight | Business Value |
|--------|---------------|
| Total Deposits (2.01Bn) exceed Total Loans (1.77Bn) | Strong liquidity & stable financial positioning |
| Loan-to-Deposit Ratio: **0.88** | Indicates low risk & healthy lending capacity |
| High-Income (200k+) customers contribute **20.35%** of deposits | Strong premium customer engagement |
| European nationality group has highest loan allocation | Identifies profitable geo-demographic segment |
| Positive YOY trend growth | Shows increasing customer participation |

---

## 🧮 DAX & KPI Measures
| Measure | Formula | Purpose |
|---------|---------|---------|
| Total Bank Loans | `SUM(Banking[Bank Loans])` | Total lending |
| Total Bank Deposits | `SUM(Banking[Bank Deposits])` | Total deposit inflow |
| Total Customers | `COUNT(Banking[Client ID])` | Customer base |
| Loan-to-Deposit Ratio | `[Total Bank Loans] / [Total Bank Deposits]` | Liquidity measurement |
| YOY Loan Growth % | DAX with DATEADD | Performance trend |

---

## 🛠 Tech Stack
| Tool / Tech | Usage |
|------------|-------|
| Power BI | Dashboard visualizations |
| Power Query | Data transformation & modelling |
| SQL (Jupyter Notebook) | Data cleaning, aggregation, exploratory insights |
| Python | Data validation and support analysis |
| DAX | KPI measures & calculations |
| Excel / CSV | Dataset source |
| GitHub | Repository and documentation |

---

## 📂 Project Structure
