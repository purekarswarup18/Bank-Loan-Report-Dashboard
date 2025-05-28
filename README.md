
# Bank Loan Analysis Dashboard

📌 Problem Statement
This Power BI dashboard project aims to help banks assess the overall performance of their loan portfolio. By analyzing key metrics such as loan application trends, funded vs. received amounts, good vs. bad loans, interest rates, and borrower profiles, financial institutions can make data-driven decisions and improve lending strategies.

The goal is to:

Track loan distribution over time, across regions, and among customer demographics.

Compare good vs. bad loans in terms of volume, funding, and repayments.

Understand the effect of employment length, loan purpose, and home ownership on loan outcomes.

# Steps Followed
🔹 Step 1: Data Preparation
Imported data from MS SQL Server into Power BI.
Cleaned and transformed it using Power Query (nulls, data types).
Created a date table for accurate time-based analysis.

🔹 Step 2: KPI Creation
Created DAX measures for key metrics: Total Applications, MTD, MoM.
Included Funded Amount, Received Amount, Avg. Interest Rate, and DTI.
Enabled dynamic and insightful KPI tracking.

🔹 Step 3: Loan Status Insights
Classified loans into Good and Bad categories.
Visualized application counts, funding, and repayments for both.
Displayed percentage distribution using intuitive visuals.

🔹 Step 4: Detailed Dashboards Created

📊 Dashboard 1: Summary
KPI Cards: Total Applications, Funding, Received Amount, Avg Interest, Avg DTI.

Grid view by loan status for comparative analysis.

Snap of Dashboard 1 :
 
 ![Image](https://github.com/user-attachments/assets/1fcdc4cf-6ffe-450e-a483-42ce81eda425) 

📈 Dashboard 2: Overview
Monthly Trends (Line Chart): Identifies seasonality and loan volume patterns.
Regional Analysis (Filled Map): Highlights state-wise lending behavior.
Loan Term Distribution (Donut Chart).
Employment Length (Bar Chart).
Loan Purpose (Bar Chart).
Home Ownership Impact (Tree Map).

Snap of Dashboard 2 : 

![Image](https://github.com/user-attachments/assets/f2d48ade-3e2d-4af7-9ebd-dc9fca8cd878)

📋 Dashboard 3: Details
Tabular grid with detailed borrower and loan-level information.

Enables filtering, slicing, and drill-down of loan metrics.

Snap of Dashboard 3 :

![Image](https://github.com/user-attachments/assets/ed339e36-cbd5-4829-8b71-550f9bbcf0b3)

🧠 Key Insights
[1] Loan Status Overview:
Good Loan Applications: XX%

Bad Loan Applications: XX%

Good Loan Funded Amount: $XXX,XXX

Bad Loan Funded Amount: $XXX,XXX

[2] Financial KPIs:
Total Loan Applications: XXXX

Total Funded Amount: $XXX,XXX

Total Received Amount: $XXX,XXX

Average Interest Rate: X.XX%

Average DTI: X.XX

[3] Demographic & Behavioral Trends:
Majority of borrowers are returning customers.

Most loans are issued for debt consolidation.

Highest loan activity is observed in the XX state(s).

Borrowers with 2–5 years employment are most common.

📚 Tools & Technologies Used
Power BI (June 2023 Version)

MS SQL Server 2019

SQL Server Management Studio

Microsoft Excel 2021


