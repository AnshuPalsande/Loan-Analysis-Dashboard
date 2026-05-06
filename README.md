# LendScope – Data Driven Loan Analysis

## Overview
LendScope is a data-driven loan analytics project built using SQL, Power BI, and Python to analyze financial loan data and generate business insights related to loan performance, customer behavior, repayment trends, and risk analysis.

The project focuses on transforming raw loan data into interactive dashboards and meaningful KPIs that help financial institutions monitor loan distribution, repayment performance, and default risk.

---

# Project Objectives

- Analyze loan application and repayment trends
- Identify high-risk and low-risk loan segments
- Track funded amount, total payments, and loan status
- Understand customer financial behavior using income, DTI, and employment data
- Build interactive dashboards for business decision-making

---

# Tech Stack

- **SQL** – Data cleaning, transformation, KPI calculations
- **Power BI** – Interactive dashboard creation and visualization
- **Python (Pandas)** – Data preprocessing and validation
- **CSV Dataset** – Financial loan records dataset

---

# Dataset Information

The dataset contains financial loan records with customer and transaction-related information.

## Main Columns Used

| Column | Description |
|---|---|
| id | Unique loan ID |
| address_state | Customer state |
| application_type | Individual or joint application |
| emp_length | Employment duration |
| grade | Loan grade assigned by lender |
| home_ownership | Ownership status |
| issue_date | Loan issue date |
| loan_status | Current loan status |
| purpose | Purpose of loan |
| annual_income | Customer annual income |
| dti | Debt-to-income ratio |
| int_rate | Interest rate |
| loan_amount | Total funded loan amount |
| installment | Monthly installment |
| total_payment | Total amount repaid |

---

# Key KPIs

The dashboard tracks multiple financial and operational KPIs:

- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average Debt-to-Income Ratio
- Good Loan Percentage
- Bad Loan Percentage
- Loan Status Distribution
- Monthly Loan Trends
- State-wise Loan Analysis

---

# Dashboard Features

## 1. Summary Dashboard

Provides an overview of:

- Total applications
- Funded amount
- Total received amount
- Good vs bad loans
- Average interest rate
- Average DTI

## 2. Loan Performance Dashboard

Tracks:

- Loan status distribution
- Fully paid vs charged-off loans
- Monthly loan trends
- Revenue generated from repayments

## 3. Customer Analysis Dashboard

Analyzes:

- Employment length
- Home ownership patterns
- Income distribution
- Loan purpose categories
- State-wise loan applications

---

# Data Cleaning & Transformation

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Standardized date formats
- Converted percentage values into numeric format
- Validated financial columns
- Created calculated measures and KPIs

---

# SQL Analysis Performed

Example SQL operations used:

- Aggregate calculations
- Loan status segmentation
- Monthly trend analysis
- Average interest calculations
- Grouping and filtering operations
- KPI generation queries

---

# Business Insights

The project helps identify:

- High-risk loan categories
- Customer segments with higher default probability
- States with maximum loan applications
- Relationship between income and repayment behavior
- Impact of interest rate on loan performance

---

# Project Files

| File | Description |
|---|---|
| financial_loan.csv | Raw loan dataset |
| LendScope - Data Driven Loan Analysis.pbix | Power BI dashboard file |
| LendScope - Data Driven Loan Analysis.sql | SQL queries used for analysis |

---

# Tools & Skills Demonstrated

- Data Cleaning
- Data Transformation
- SQL Query Writing
- KPI Development
- Financial Analytics
- Dashboard Design
- Business Intelligence
- Data Visualization

---

# Future Improvements

Potential future enhancements:

- Add machine learning-based loan default prediction
- Deploy dashboards online using Power BI Service
- Automate ETL pipeline
- Add real-time loan monitoring
- Integrate customer credit score analysis

---

# Conclusion

LendScope demonstrates how data analytics and business intelligence tools can be used to transform raw financial loan data into actionable insights. The project showcases end-to-end analytics skills including data cleaning, SQL analysis, KPI development, and dashboard visualization.

This project is suitable for showcasing skills related to:

- Data Analyst Roles
- Business Intelligence Roles
- Financial Analytics
- Banking & Risk Analytics
- Power BI Developer Roles
