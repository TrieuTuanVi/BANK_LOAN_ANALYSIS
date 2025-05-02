# [![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)](https://www.tableau.com/) Tableau Project - BANK LOAN ANALYSIS PROJECT 💰💰💰 | SQL + TABLEAU 

This project aims to analyze banking loan data to assess loan performance, identify customer behavior patterns, and provide actionable insights for business decision-making. By leveraging SQL for data transformation and Tableau for dynamic visualization, we build an interactive dashboard that helps monitor loan status, customer segments, and financial risks.

---

## 🎯 Project Objectives

- Evaluate the performance of issued loans (Good vs Bad loans)
- Discover patterns in loan repayment and defaults
- Analyze key factors influencing loan outcomes: term, purpose, grade, interest rate,...
- Design a comprehensive dashboard for data-driven decision-making

---

##  📁 Dataset 

- <a href= "https://github.com/TrieuTuanVi/BANK_LOAN_ANALYSIS/blob/main/financial_loan.csv">Dataset</a> 
- The dataset includes over 38,576 loan records with fields such as: borrower information, loan information, date information, payment information

---

## 🛠 Tools 

- [![SQL](https://img.shields.io/badge/SQL-003B57?style=flat&logo=mysql&logoColor=white)](https://www.mysql.com/) : Data cleaning, transformation and querying
- [![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)](https://www.tableau.com/) : Visualization and dashboard creation
- [![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel) (supporting tool) : For initial exploration and validation

---

## ⚙️ Workflow

1️⃣ **Data Preparation**: Cleaned and loaded raw data into SQL, removed nulls, standardized columns.

2️⃣ **Feature Engineering**:

  - Classified loan status into Good (Current, Fully Paid) and Bad (Charged Off, Late, Default)
  - Calculated metrics like average interest rate, total disbursed amount, average DTI, etc

3️⃣ **Aggregation**: Created summary tables grouped by purpose, term, grade, and loan status.

4️⃣ **Visualization**: Built a Tableau dashboard with 3 main views:

  - **Summary**: High-level KPIs and performance ratios
  - **Overview**: Detailed breakdown by dimensions (time, term, ownership, purpose)
  - **Details**: Raw loan-level data for drill-down

---

## 📊 Dashboard Overview
