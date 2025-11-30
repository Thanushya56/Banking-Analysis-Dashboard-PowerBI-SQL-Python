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

📁 Banking-Analysis-Dashboard
├── 📊 bankinganalysis.pbix
├── 📄 Banking_Analysis_Documentation.pdf / .docx
├── 📁 Screenshots
│ ├── Home.png
│ ├── LoanAnalysis.png
│ ├── DepositAnalysis.png
│ └── Summary.png
├── 📁 Dataset
│ └── Banking.csv
├── 📓 bankingpython.ipynb
└── README.md

Dashboard screenshots
<img width="1435" height="803" alt="image" src="https://github.com/user-attachments/assets/b90046cb-afb3-44ff-9f65-c109469f4556" />

<img width="1431" height="801" alt="image" src="https://github.com/user-attachments/assets/3751fd18-7561-44cf-a7f9-5fc5783915ec" />

<img width="1429" height="801" alt="image" src="https://github.com/user-attachments/assets/6131b48b-0f4a-4f93-beed-05822d5ea2f2" />

<img width="1432" height="799" alt="image" src="https://github.com/user-attachments/assets/3e8efbf2-430d-4cac-9236-64d19a6a7b7b" />


---

## 🔗 Project Flow
**SQL + Python ➜ Data Cleaning ➜ Power Query Modeling ➜ DAX KPIs ➜ Interactive Power BI Dashboard ➜ Insights & Recommendations**

---

## 📍 Future Enhancements
- Real-time SQL database connection with auto refresh
- RLS (Role Level Security)
- ML forecasting for loan default predictions
- Automated Power BI web embedding

---

## 🙋‍♀️ About Me
**Thanushya Elugam **  
🔍 Passionate about building data-driven business solutions  
💼 Open to Data Analyst / BI Analyst / Power BI roles  
📨 Let’s connect!

---

## 🔗 Connect With Me
| Platform | Link |
|-----------|-------|
| LinkedIn | (https://www.linkedin.com/in/thanushya-elugam) |
| GitHub | (https://github.com/Thanushya56) |

---

### ⭐ If you like this project, please star the repository!

