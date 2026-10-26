# 💳 OPay Financial Activity Analysis

## Problem Statement
Managing personal finances across multiple accounts can be challenging without clear visibility into spending and saving patterns. Without proper analysis, it becomes difficult to track cash flow, identify spending habits, and evaluate savings performance. This creates a need for a structured and data-driven approach to monitor wallet and savings account activities.

---

## Objectives
The aim of this project is to analyze wallet and savings transactions over the past year to uncover financial trends and patterns.
Specifically, the analysis seeks to:

- Evaluate cash inflow and outflow across both accounts
- Identify spending and saving behaviors
- Track monthly and quarterly performance trends
- Measure financial growth and stability over time

---

## Data Description
The financial dataset consists of two Excel sheets:

1. Wallet Account Transactions
> Contains all day-to-day financial activities such as transfers, airtime, bills, and other expenses. It includes details like transaction date, description, debit, credit, and transaction channel.

2. Savings Account Transactions
> Captures savings-related activities including deposits, withdrawals, and automated savings. It provides insights into savings behavior and long-term financial discipline.

---

## Data Preparation
The dataset was imported into Excel and processed using Power Query to ensure consistency, accuracy, and readiness for analysis.

---

## Data Cleaning and Transformation
Using Power Query:
- Standardized and corrected data types for key columns such as Debit and Credit
- Ensured consistency across both wallet and savings datasets
- Handled missing or inconsistent values where necessary
- Create a data table (calendar) for time intelligence

---

## Feature Engineering
A new column, “Transaction Type,” was created to categorize transactions based on their descriptions.

Examples include:
- Transfers: Transfer, USSD Charges
- Savings: OWealth Deposit, OWealth Withdrawal
- Bills & Services: Airtime, Electricity, Mobile Data
  
This improved the clarity and depth of analysis.

---

## Data Modeling
Using Power Pivot, create a relationship between the tables with the data table (calendar) for time intelligence.
This allows seamless data filters.

---

## Exploratory Data Analysis (EDA)
Pivot Tables were used to explore performance and uncover insights, including:
- Monthly Credits vs Debits trends
- Quarterly wallet and savings statements
- Total transaction counts across both accounts
- Category-level spending and saving patterns
- Create KPIs for the both accounts 

## Dashboard Overview	
The dashboard provides a comprehensive view of OPay wallet and savings account activities, highlighting debits, credits, cash flow patterns, and overall financial performance over the past year (MoM trend).




