Credit Card Power BI Project

Overview 
This project aims to analyze credit card usage and customer data using Power BI. We will perform data cleaning using Excel, extract valuable KPIs using SQL, and create insightful visualizations and dashboards using Power BI.

Project Structure

Data Sources:
credit_card.xlsx
customer.xlsx

Tools Used:
Excel (for data cleaning)
SQL (for KPI extraction)
Power BI (for data visualization and dashboard creation)

Steps to Reproduce
1. Data Cleaning
Tool: Excel
Process:
Remove duplicates
Handle missing values
Normalize data formats (e.g., date formats)
Ensure data consistency across files

2. Data Analysis
Tool: SQL
Process:
Import cleaned data into a SQL database
Write SQL queries to extract valuable KPIs:
Total revenue
Total interest earned
Total transaction amount
Total transaction count
Total income
Customer satisfaction score (CSS)

3. Data Visualization
Tool: Power BI
Process:
Import data from SQL database
Create interactive dashboards and reports to visualize the KPIs
Use various Power BI visualizations such as bar charts, line graphs, and tables to represent data effectively

4. Key Performance Indicators (KPIs)
Total Revenue: Sum of all transaction amounts
Total Interest: Sum of all interest earned
Transaction Amount: Total transaction amount for each customer
Transaction Count: Number of transactions for each customer
Total Income: Sum of all customer incomes
Customer Satisfaction Score (CSS): Average satisfaction score across all customers

5. Project Structure
data/: Contains the Excel files (credit_card.xlsx and customer.xlsx)
sql/: Contains SQL scripts for data extraction and KPI calculation
powerbi/: Contains the Power BI project file (CreditCardDashboard.pbix)
README.md: Project documentation (this file)

6. Usage
Data Cleaning: Open the Excel files in the data/ directory and perform the necessary cleaning steps.
Data Analysis: Use the SQL scripts in the sql/ directory to extract and calculate the KPIs.
Data Visualization: Open the Power BI project file in the powerbi/ directory to view and interact with the dashboard.
