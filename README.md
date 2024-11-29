# Credit card Weekly status Report


### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiZDlhMjI0NGQtNjBiMy00YmFkLWI3ZTAtMThiNTVhYmI3NmYyIiwidCI6ImVkNTcxY2M5LWYxNGUtNGFiOS1hZjY4LTkzOTIyNjY0ZWQzZiJ9

## Overview

This Power BI dashboard provides a comprehensive analysis of credit card transactions, revenue, customer demographics, and key performance indicators. It offers interactive visualizations and data analysis tools to understand spending patterns, identify valuable customer segments, and track trends over time.

## Key Metrics and Visualizations

### 1. Revenue Analysis:

- Total revenue generated from credit cards.
- Revenue breakdown by card category (Blue, Silver, Gold, Platinum)
- Revenue contribution by education type, customer job, marital status, and income group.
- Quarterly revenue trends.


### 2. Transaction Analysis:

- Total transaction amount.
- Transaction breakdown by method (Swipe, Chip, Online).
- Top 5 states for transactions.

### 3. Customer Demographics:

  - Total income generated from all customers.
  - Customer distribution by age group.
  - Revenue contribution by customer job and income group.

### 4. Interest Earned:
  - Total interest earned from credit card transactions.

### 5. Interactive Visualizations:
  - Bar charts, line graphs, and maps to visualize data.
  - Filters and slicers to drill down into specific data segments.
## Steps followed 

- `Step 1` : Importing Data from CSV file to MS SQL Server.
- `Step 2` : Creating a new Data base PostgreSQL Server and Firing queries to solve the business problems
- `Step 3` : Importing data from  SQL Server to Power BI desktop.
- `Step 4` : Creating an interactive dashboard in PowerBI.
- `Step 5` : Validating Results generated in PowerBI with SQL Server.
- `Step 6` : Publishing the dashboard to PowerBI Service.

## File Structure

- **`credit_card_report.pbix`**: The Power BI file containing the dashboard design and data model.
- **`credit_card.csv`,`customer.csv`,`cc_add.csv`,`cust_ad.csv`**: The raw dataset used to create the dashboard.
- **`DAX Queries.docx`**: DAX Queries used for the project
- **`README.md`**: This documentation file.
- **` Preview1.jpg, Preview2.jpg`**: A preview of the Bank Loan Anlysis Dashboard for quick reference.


## Snapshot of Dashboard (Power BI Service)
![Preview1](https://github.com/user-attachments/assets/1ed4575d-8115-4d4d-b0e4-23337fde4fd6)
![Preview2](https://github.com/user-attachments/assets/d516dc6b-6f03-4847-9fb5-5893b2a75b67)

 


# Key Insights


-  Total revenue generated from credit cards is `57 million`.
-  Revenue shows an `increasing trend` over time.
-  `Blue Card` Category is the dominant contributor to revenue `(82%)`
-  `Businessmen` are the most valuable customer group with the highest revenue `(32%)`
-  Most transactions are done via `Swipe Mode` `(63%)`
-  Most Revenue Generated from the age group `40-50` `(44%)`
-  `Graduate` Customers provide the highest revenue`(40%)`
-  `Male` customers genarates a slightly higher total revenue than females `(54%)`
-  `Married` customers genarates a slightly higher overall revenue compared to single customers `(51%)`
-  The `High` income group contributes the most revenue `(41%)`
-  States `Texas`,`New York`,`California`,`Florida`and`New Jersey` all together contribute `92%` of the revenue.



## Software Used

- **Power BI Desktop** - Version: 2.136.1202.0 
- **PostgreSQL**- 17.0
- **Microsoft Office**-Version 2021

