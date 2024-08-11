# Financial-Loan-Power-BI-Dashboard
The objective of this project is to create an interactive Power BI dashboard that helps to get decisions regarding loan management, customer targeting, risk assessment, and overall business strategy and 
Provide actionable insights through interactive reports and dashboards. 

# Problem Statement:
Design a Power BI dashboard to analyse and visualize the financial loans. The dashboard should provide insights into the following aspects:
1.	Loan Distribution: Display the distribution of loan types (e.g., personal loans, home loans, car, business loans …) by count and amount disbursed.
2.	Loan Performance: Show the overall performance of loans by visualizing metrics such as total amount disbursed, total amount repaid.
3.	Loan Payment Status: Analyse the loan status rates across different loan types and customer segments. Good loan vs Bad loan.
4.	Customer Segmentation: Segment customers based on loan types and demographics (e.g., state, grade, home-ownership, age, income level) to understand the bank’s target market and potential growth areas.
5.	Geographical Analysis: Provide a geographical view of loan distribution and performance using maps and regional insights.
6.	Trends and Forecasts: Identify trends in loan applications over time and provide forecasts for future loan demand based on historical data. (month wise)
7.	Fraud Detection: use data analysis to detect fraudulent loan applications and activities. Unusual patterns, inconsistencies, or discrepancies in loan data can trigger fraud alerts.
8.	Key Performance Indicators (KPIs): Highlight important KPIs such as loan application funded amount, receive amount, interest rate, DTI.


![powerbiprogect1](https://github.com/user-attachments/assets/5bf27907-54c2-4ac6-a90e-59b00561ad76)


![powerbiproject2 1](https://github.com/user-attachments/assets/c65903a7-036b-42ef-8187-489ee117bcd9)


![powerbiprojecct3](https://github.com/user-attachments/assets/0e42be33-527c-4085-b3b9-5e7b76f0a5ed)

# Step-by-Step Project Approach:
# Step 1: Data Gathering and Preparation
1.	Data Sources: Get the data from Kaggle (CSV file) 
2.	Extract Data: Use Power BI to connect to and extract data. (Power BI supports a wide range of data connectors.)
3.	Transform Data: Clean, transform, data using Power Query Editor to prepare it for Dashboard creation. Tasks may include filtering rows, handling missing values, creating calculated columns (Good vs Bad), calculated table (Date) etc.
# Step 2: Data Modelling
1.	Create Relationships: Define relationships between tables in the data model. (connect the “date” table to “financial_loan (data)” table. One to Many Relationship)
2.	Optimize the Model: Improve performance by removing unnecessary columns, creating calculated tables or columns, and ensuring data types are appropriate.
# Step 3: Report Design
1.	Create Visualizations: Design various visualizations (charts, graphs, tables, maps, etc.) based on the defined objectives and requirements.
2.	DAX (Data Analysis Expressions): use DAX measures to calculate key metrics and KPIs that provide insights into your data (Total Loan Application, Total Funded Amount, Total Receive Amount … etc)
3.	Arrange Visuals: Organize visuals on report pages to provide a clear and logical flow of information.
4.	Apply Filters and Slicers: Use filters, slicers, and other interactive elements to allow users to explore the data dynamically.
# Step 4: Dashboard Creation
1.	Design Dashboards: Aggregate key visuals and KPIs from multiple report pages into a single dashboard.
2.	Apply Interactivity: Ensure the dashboard is interactive and allowing users to filter data based on their needs.

