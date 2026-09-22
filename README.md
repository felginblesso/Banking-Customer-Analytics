# Banking-Customer-Analytics
## Project Overview

This project focuses on analyzing banking customer data to understand customer characteristics, financial behavior, loan and deposit patterns, and risk-related attributes.

The project follows an end-to-end analytics workflow using Python for data preprocessing and exploratory data analysis, MySQL for data storage, and Power BI for interactive dashboard reporting.

---

## Objectives

- Analyze customer demographics and financial characteristics
- Perform data cleaning and preprocessing
- Explore relationships between key banking attributes
- Analyze customer loan and deposit patterns
- Examine income bands and customer financial behavior
- Analyze banking metrics across customer segments
- Explore risk-weighting distribution
- Build interactive Power BI dashboards
- Convert analytical findings into business-oriented insights

---

## Tools & Technologies

- **Python** – Data preprocessing and exploratory data analysis
- **Pandas** – Data manipulation and analysis
- **Matplotlib & Seaborn** – Data visualization
- **MySQL** – Data storage
- **Power BI** – Interactive dashboards and reporting
- **Excel** – Source dataset

---

## Dataset

The dataset contains customer-level banking information covering demographic, income, savings, loans, deposits, account balances, credit cards, and other financial attributes.

### Key Attributes

- Customer ID
- Age
- Joined Bank
- Nationality
- Occupation
- Estimated Income
- Superannuation Savings
- Credit Card Balance
- Bank Loans
- Bank Deposits
- Checking Accounts
- Saving Accounts
- Foreign Currency Account
- Business Lending
- Properties Owned
- Risk Weighting
- Income Band

---

# Dashboard

An interactive Power BI dashboard was created to provide a consolidated view of customer and banking analytics.

The report contains four main pages:

## 1. Home

The Home page provides an entry point to the Power BI report and allows users to navigate between the different analytical sections and the key KPI's.

The report navigation includes:

- Home
- Loan Analysis
- Deposit Analysis
- Summary

Interactive filters and navigation elements are provided to explore the report based on different customer and banking dimensions.

---

## 2. Loan Analysis

The Loan Analysis page focuses on customer lending and credit-related metrics.

### Key Metrics

- Total Loan
- Bank Loan
- Business Lending
- Credit Card

### Analysis Included

- Bank Loan by Banking Relationship
- Bank Loan by Occupation
- Bank Loan by Income Band
- Bank Loan by Nationality

The page also provides interactive filtering by:

- Year
- Banking segment
- Investment Advisor

This allows users to examine loan patterns across different customer groups and time periods.

---

## 3. Deposit Analysis

The Deposit Analysis page focuses on customer deposits and account balances.

### Key Metrics

- Total Deposit
- Bank Deposit
- Saving Account
- Checking Amount

### Analysis Included

- Bank Deposit by Banking Relationship
- Bank Deposit by Occupation
- Bank Deposit by Income Band
- Bank Deposit by Nationality

Interactive filters allow users to analyze deposit patterns based on:

- Year
- Banking segment
- Investment Advisor

---

## 4. Summary

The Summary page provides a consolidated view of the key banking and customer metrics analyzed throughout the report.

It is designed to help users quickly review important insights from the different analytical sections without navigating through individual detailed views.

---

# Key Analysis

The exploratory analysis examined customer demographics, income, banking balances, loans, deposits, account balances, and risk-related attributes.

The analysis identified patterns across:

- Customer income levels
- Loan distribution
- Deposit distribution
- Banking segments
- Occupations
- Nationalities
- Income bands
- Account balances
- Risk-weighting levels

The Power BI dashboard converts these analytical results into interactive visual reports that allow users to explore the data across different years, customer segments, and investment advisors.

---

# Project Structure

```text
Banking-Customer-Analytics/
│
├── data/
│   └── banking.csv
│
├── python/
│   └── banking.ipynb
│
├── sql/
│   └── banking_customer.sql
│
├── powerbi/
│   └── Banking Dashboard.pbix
│
├── screenshots/
│   ├── Home.png
│   ├── Loan Analysis.png
│   ├── Deposit Analysis.png
    ├── Summary.png
│   └── Icon Logo/
│
└── README.md

