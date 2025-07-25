# banking-eda-powerbi-dashboard
### 1. Data Understanding & Exploration (EDA)
- Explored a multi-table banking dataset containing client, account, and loan information.
- Identified how tables are connected using primary and foreign keys.
- Focused on key features such as loan amounts, deposit types, client demographics, and engagement duration to guide further analysis.
### 2. Feature Engineering
- Created new columns to enhance the dataset for better analysis:
  - `Engagement Days`: Calculated how long a client has been with the bank using `DATEDIFF`.
  - `Income Band`: Grouped estimated income into categories like Low and Mid.
  - `Processing Fees`: Assigned a 0.05 fee rate for clients with a high fee structure.
- These features helped in calculating KPIs and building more insightful visuals.
- ### 3. KPI Calculations (with DAX)
- Used DAX functions in Power BI to calculate key performance indicators:
  - `Total Clients` using `DISTINCTCOUNT`
  - `Total Loan`, `Bank Loan`, and `Business Lending` using `SUM`
  - `Total Fees` using `SUMX` with the formula: Total Loan × Processing Fees
  - `Engagement Days` and other derived metrics using `DATEDIFF` and `SWITCH`
- These KPIs formed the core of the dashboard insights.
- ### 4. Power BI Dashboarding
- Built an interactive Power BI dashboard with multiple views:
  - **Loan Analysis**: Showed Bank Loans, Credit Card Balances, and Business Lending.
  - **Deposit Analysis**: Displayed Savings, Checking, and Foreign Currency deposits.
  - **Summary Dashboard**: Highlighted Total Clients, Total Loans, Total Deposits, and Engagement.
- Added slicers/filters for Gender, Bank Type, Nationality, and Income Band to make the dashboard dynamic and user-friendly
<img width="1166" height="658" alt="Screenshot 2025-07-25 114020" src="https://github.com/user-attachments/assets/82ed8079-8f5e-45f2-918e-8c327e787ab6" />
 
<img width="1168" height="653" alt="Screenshot 2025-07-25 113950" src="https://github.com/user-attachments/assets/6750a07d-c98e-4dce-95c8-6425795e9cfc" />

<img width="1165" height="654" alt="Screenshot 2025-07-25 114038" src="https://github.com/user-attachments/assets/8f6c935c-d586-4a12-b50f-5ee63e35040c" />
