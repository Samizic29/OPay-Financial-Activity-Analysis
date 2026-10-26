# 💳 OPay Financial Activity Analysis

## Problem Statement
Managing personal finances across multiple accounts can be challenging without clear visibility into spending and saving patterns. Without proper analysis, it becomes difficult to track cash flow, identify spending habits, and evaluate savings performance. This creates a need for a structured and data-driven approach to monitor wallet and savings account activities.

---

## Objectives
The aim of this project is to analyze wallet and savings transactions over the past year to uncover financial trends and patterns.
Specifically, the analysis seeks to:

- Evaluate **cash inflow and outflow** across both accounts
- Identify **spending and saving behaviors**
- Track **monthly and quarterly performance trends**
- Measure **financial growth and stability** over time

---

## Data Description
The financial dataset consists of two Excel sheets:

1. **Wallet Account Transactions**
> Contains all day-to-day financial activities such as transfers, airtime, bills, and other expenses. It includes details like transaction date, description, debit, credit, and transaction channel.

2. **Savings Account Transactions**
> Captures savings-related activities including deposits, withdrawals, and automated savings. It provides insights into savings behavior and long-term financial discipline.

---

## Data Preparation
The dataset was imported into Excel and processed using **Power Query** to ensure consistency, accuracy, and readiness for analysis.

<img width="901" height="481" alt="Import Data(Power Query)" src="https://github.com/user-attachments/assets/0a23447d-1965-4f1c-a9e0-4c3f8411e5d7" />


---

## Data Cleaning and Transformation
Using Power Query:
- Standardized and corrected **data types** for key columns such as Debit and Credit
- Ensured consistency across both wallet and savings datasets
- Handled missing or inconsistent values where necessary
- Create a data table (calendar) for time intelligence

---

## Feature Engineering
A new column, “**Transaction Type,**” was created to categorize transactions based on their descriptions.

Examples include:
- **Transfers**: Transfer, USSD Charges
- **Savings**: OWealth Deposit, OWealth Withdrawal
- **Bills & Services**: Airtime, Electricity, Mobile Data
  
This improved the clarity and depth of analysis.

---

## Data Modeling
Using Power Pivot, create a relationship between the tables with the data table (calendar) for time intelligence.
This allows seamless data filters.

---

## Exploratory Data Analysis (EDA)
Pivot Tables were used to explore performance and uncover insights, including:
- Monthly **Credits vs Debits trends**
- **Quarterly wallet and savings statements**
- Total **transaction counts** across both accounts
- Category-level spending and saving patterns
- Create KPIs for the both accounts

---

## Dashboard Overview	
The dashboard provides a comprehensive view of OPay wallet and savings account activities, highlighting **debits, credits, cash flow patterns, and overall financial performance** over the past year (MoM trend).

**Key KPIs** using DAX Measures

**Wallet Account**
- Total Credits
- Total Debits
- Net Balance
- Total Transactions 

**Savings Account**
- Total Deposits
- Total Withdrawals
- Net Growth
- Total Transactions 

**MoM trend**
- Previous Month (PM)
- MoM%

### Wallet Account Transaction Overview Dashboard
> Tracks wallet inflows and outflows to understand spending behavior and cash flow patterns.

<img width="992" height="45" alt="image" src="https://github.com/user-attachments/assets/b0a1c825-fdea-4877-82a0-eaba3552dda0" />

### Savings Account Performance Analysis Dashboard
> Analyze deposits, withdrawals, and net growth to evaluate savings performance over time.

<img width="976" height="45" alt="image" src="https://github.com/user-attachments/assets/be5dd703-49f7-44d2-8161-ae3d17f37db7" />

---

## Key Insights

💳 **Wallet Account**
- Recorded **1.34K transactions**, with **454 credits** and **886 debits**.
- Total Credits: **₦3.27M**, Total Debits: **₦3.26M**, resulting in a **net balance of ₦8.63K**. 
- **November** had the highest activity, with both credits and debits peaking and generating the highest net balance.
- There is a steady increase in transaction activity across quarters, with **Q4 recording the highest volume**.
- A significant portion of spending is on **electricity (excluding transfers)**.
- Most transactions were conducted via **mobile channels**, indicating high digital usage.
  
💰 **Savings Account**
•	Recorded **574 transactions**, including **395 deposits** and **179 withdrawals**. 
•	Total Deposits: **₦607.10K**, Total Withdrawals: **₦589.54K**, with a **net growth of ₦17.56K**. 
•	**November** recorded the highest deposits and withdrawals but showed relatively low net growth. 
•	**December** had no withdrawal transactions, indicating strong saving behavior. 
•	**Q4 had the highest transaction volume**, while **Q1 recorded the highest net savings growth**. 
•	Net savings growth fluctuated throughout the year, reflecting inconsistent saving patterns. 

---

## Recommendations
- Control High Utility Spending: Since electricity accounts for a large portion of expenses, consider budgeting or monitoring usage to reduce costs.
- Leverage High-Income Periods: Months like November with high inflows can be optimized by allocating more funds to savings or investments.
- Improve Savings Consistency: The fluctuation in savings growth suggests the need for more structured saving habits, such as automated savings plans.
- Encourage Financial Discipline: Maintaining months like December (with zero withdrawals) can significantly improve long-term financial stability.
- Monitor Cash Flow Balance: With wallet credits and debits nearly equal, better expense tracking can help increase net balance over time.  

---

## Conclusion
This analysis provides valuable insights into personal financial behavior across wallet and savings accounts. While transaction activity is high and consistent, spending patterns—particularly on utilities—limit overall financial growth.
By adopting better budgeting strategies and maintaining consistent savings habits, there is strong potential to improve financial stability and achieve sustainable growth.

---

## 📌 Tools Used
- **Excel** → Power Query, Power Pivot, DAX, VBA
- **GitHub** for project versioning

---

## 📝 Author
### Samuel Oyedele
**Data Analyst | BI Developer**

Feel free to reach out for feedback, collaboration, or project discussions.

🔗 [LinkedIn Profile](https://www.linkedin.com/in/oyedele-samuel-53579b19b)
    
    Email: samueloyedele15@gmail.com

  
