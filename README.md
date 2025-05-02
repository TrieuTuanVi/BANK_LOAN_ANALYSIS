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

The dataset includes over 38,000 loan records with fields such as: id,	address_state,	application_type,	emp_length,	emp_title,	grade	home_ownership	issue_date	last_credit_pull_date	last_payment_date	loan_status	next_payment_date	member_id	purpose	sub_grade	term	verification_status	annual_income	dti	installment	int_rate	loan_amount	total_acc	total_payment
![image](https://github.com/user-attachments/assets/8a8f6d4e-43be-41eb-9082-063c565b5010)

---

## 🛠 Tools Used

SQL: Data cleaning, transformation, aggregation.

Tableau: Visualization and dashboard creation.

Excel (supporting tool): For initial exploration and validation.

---

## 🔄 Project Workflow

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

---

## 📊 Dashboard Overview
