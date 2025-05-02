# [![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)](https://www.tableau.com/) Tableau Project - BANK LOAN ANALYSIS PROJECT 💰💰💰 | SQL + TABLEAU 

This project aims to analyze banking loan data to assess loan performance, identify customer behavior patterns, and provide actionable insights for business decision-making. By leveraging SQL for data transformation and Tableau for dynamic visualization, we build an interactive dashboard that helps monitor loan status, customer segments, and financial risks.

---

## 🎯 Objectives: 

- Evaluate the performance of issued loans (Good vs Bad loans)
- Discover patterns in loan repayment and defaults
- Analyze key factors influencing loan outcomes: term, purpose, grade, interest rate,...
- Design a comprehensive dashboard for data-driven decision-making

---

##  📁 Dataset:

- <a href= "https://github.com/TrieuTuanVi/BANK_LOAN_ANALYSIS/blob/main/financial_loan.csv">Dataset</a> 
- The dataset includes over 38,576 loan records with fields such as: borrower information, loan information, date information, payment information

---

## 🛠 Tools:

- [![SQL](https://img.shields.io/badge/SQL-003B57?style=flat&logo=mysql&logoColor=white)](https://www.mysql.com/) : Data cleaning, transformation and querying
- [![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)](https://www.tableau.com/) : Visualization and dashboard creation
- [![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel) (supporting tool) : For initial exploration and validation

---

## ⚙️ Workflow:

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

## 📊 Dashboard:

- **DASHBOARD 1: SUMMARY**
  
**1. Key Performance Indicators (KPIs)**:
- **Total Loan Applications**: Track total applications, Month-to-Date (MTD) applications, and Month-over-Month (MoM) changes
- **Total Funded Amount**: Monitor total funds disbursed, MTD amounts, and MoM variations
- **Total Amount Received**: Analyze total repayments, MTD amounts, and MoM changes
- **Average Interest Rate**: Calculate average rates and track MTD and MoM fluctuations
- **Average Debt-to-Income Ratio (DTI**): Evaluate average DTI for borrowers and monitor MTD and MoM changes.

**2. Good vs. Bad Loan KPIs:**
- **Good Loans**: Percentage, total applications, funded amounts, and received amounts for loans classified as 'Fully Paid' or 'Current'.
- **Bad Loans**: Percentage, total applications, funded amounts, and received amounts for loans classified as 'Charged Off'.

**3. Loan Status Grid View:** A grid view report will categorize loans by status, providing insights into metrics like total applications, funded amounts, and average interest rates.

![1  SUMMARY](https://github.com/user-attachments/assets/19bdb14a-38c3-474c-99f7-20ad6f92b035)

  
- **Overview Dashboard**
![2  OVERVIEW](https://github.com/user-attachments/assets/ed0f75fc-1e12-42fd-a65a-0b8d14c25534)

  
- **Detail Dashboard**
![3  DETAILS](https://github.com/user-attachments/assets/39d73d95-c15d-401d-9d77-610cea73b214)

---

## ✅Insight: 

- **Good Loans** account for **86.2%** of the total portfolio, while **Bad Loans** make up the remaining **13.8%**, highlighting overall positive loan performance
- A significant majority of borrowers (**73.2%**) opt for **60-month loan terms**, suggesting a preference for longer repayment durations
- **Debt Consolidation** is the leading loan purpose, representing **47.2%** of total loans (18.2K out of 38.6K applications)
- **Grade B loans** are the most frequently issued, comprising over **25%** of all loans
- Borrowers with **10+ years of employment** represent **~23%** of the applicant pool (8.9K), indicating employment stability among many applicants
- Applicants who **rent their homes** account for the largest group (**~48%**) and show a higher tendency for **bad loans** compared to homeowners
- **Interest rates above 18%** are strongly associated with **Charged Off** loans, indicating higher default risk at elevated interest levels
- Customers with a **Debt-to-Income (DTI) ratio > 14%** exhibit significantly more defaults, especially in “Charged Off” and “Current” statuses
- Loans with **monthly installments above $1,200** show a higher incidence of **non-performing loans**, suggesting repayment stress in higher-value loans

---

## 🏆 Conclusion: 

The analysis reveals that while the majority of loans are performing well, higher risk is associated with long-term loans, high interest rates, and borrowers with elevated DTI or large monthly installments. These insights can support better credit assessment and portfolio management, helping lenders make more informed, data-driven decisions.




