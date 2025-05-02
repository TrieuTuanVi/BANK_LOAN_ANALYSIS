[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)](https://www.tableau.com/) Tableau:
This project aims to analyze banking loan data to assess loan performance, identify customer behavior patterns, and provide actionable insights for business decision-making. By leveraging SQL for data transformation and Tableau for dynamic visualization, we build an interactive dashboard that helps monitor loan status, customer segments, and financial risks.

🎯 Project Objectives
Evaluate the performance of issued loans (Good vs Bad loans).

Discover patterns in loan repayment and defaults.

Analyze key factors influencing loan outcomes: term, purpose, grade, interest rate, etc.

Design a comprehensive dashboard for data-driven decision-making.

📁 Data Description
The dataset includes over 38,000 loan records with fields such as:

Loan ID, Loan Status, Loan Amount, Term, Interest Rate, Issue Date

Home Ownership, Employment Length, DTI (Debt-to-Income Ratio), Purpose

Total Payment, Installment, Grade, Subgrade, and more

🛠 Tools Used
SQL: Data cleaning, transformation, aggregation.

Tableau: Visualization and dashboard creation.

Excel (supporting tool): For initial exploration and validation.

🔄 Project Workflow
Data Preparation
Cleaned and loaded raw data into SQL, removed nulls, standardized columns.

Feature Engineering

Classified loan status into Good (Current, Fully Paid) and Bad (Charged Off, Late, Default).

Calculated metrics like average interest rate, total disbursed amount, average DTI, etc.

Aggregation
Created summary tables grouped by purpose, term, grade, and loan status.

Visualization
Built a Tableau dashboard with 3 main views:

Summary: High-level KPIs and performance ratios

Overview: Detailed breakdown by dimensions (time, term, ownership, purpose)

Details: Raw loan-level data for drill-down

📊 Dashboard Overview
