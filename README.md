📌 Project Overview

This project focuses on building an end-to-end Power BI dashboard to analyze retail sales performance.
The dashboard provides insights into sales, profit, cost, returns, customer behavior, and time-based trends using advanced DAX, data modeling, and business KPIs.

🎯 Business Objectives

- Analyze overall sales and profit performance
- Understand customer demographics and purchasing behavior
- Identify top cities, income groups, and education segments
- Track Year-over-Year (YoY), Month-over-Month (MoM), and Year-to-Date (YTD) growth
- Discover seasonality and sales trends

🛠 Tools & Technologies

- Power BI
- DAX (Data Analysis Expressions)
- Data Modeling (Star Schema)
- Power Query (ETL)
- Time Intelligence

📂 Dataset Description

The dataset includes multiple tables such as:

- Calendar (Date Table)
- Customers
- Products
- Regions
- Returns
- Stores
- Transactions

Relationships are built using a snowflake schema.

📐 Data Modeling

Implemented a snowflake schema with a central fact table (Transactions) and normalized dimension tables including Products, Customers, Stores, Regions, Calendar, and Returns.

Fact table: Transactions
Dimension tables: Products, Customers, Calendar, Regions, Stores, Returns

Used a dedicated Calendar table for:
- Year, Quarter, Month, Day analysis
- Time intelligence calculations (YTD, MoM, YoY)

📈 Key Metrics (Card & KPI Visuals)

The dashboard uses Card and KPI visuals to display high-level business metrics, including:

- Total Sales
- Total Cost
- Total Profit
- Net Profit
- Total Quantity Ordered
- Total Quantity Returned
- Total Refund
- Profit Margin (%)
- Average Sales per Customer
- Return Rate (%)

All metrics are calculated using DAX measures and dynamically respond to filters and slicers.

🧮 DAX Highlights

Some important DAX concepts used:

- Aggregation functions (SUM, AVERAGE, COUNT)
- Filter context handling (CALCULATE, FILTER)
- Relationship handling (RELATED, USERELATIONSHIP)
- Time intelligence (TOTALYTD, SAMEPERIODLASTYEAR, DATEADD)
- Defensive calculations (DIVIDE to avoid divide-by-zero errors)

📊 Dashboard Pages & Insights

1️. Executive Summary
High-level KPIs (Sales, Profit, Margin)
Yearly and monthly sales trends

2️. Sales Performance Analysis
Sales by Category, Product, and Region
Contribution % analysis

3️. Customer Analysis
Average Sales per Customer
Customer distribution and behavior

4️. Time-Based Analysis
Monthly and yearly trends
YTD and MoM growth analysis

5️. Returns & Stock Analysis
Return rate calculation
Impact of returns on profit

🎯 Business Insights

- Identified top-performing product categories
- Analyzed profitability vs sales volume
- Tracked customer spending behavior
- Evaluated returns impact on overall margins
- Enabled time-based performance comparison

📁 Repository Structure
📦 Retail-Sales-PowerBI
 - 📊 Dashboard.pbix
 - 📄 README.md
 - 📂 Data
   - 📄 dataset.csv
 - 📂 Screenshots
   - 📄 dashboard_views.png

🚀 How to Use

1. Download the .pbix file
2. Open in Power BI Desktop
3. Refresh data (if required)
4. Explore dashboard using slicers and filters

📌 Skills Demonstrated

- Data Analysis & Visualization
- Business KPI Design
- DAX (Basic to Advanced)
- Data Modeling Best Practices
- Analytical Thinking

👩‍💻 Author

Unzila
Aspiring Data Analyst | Power BI | SQL | Python

⭐ If you like this project

Give the repo a ⭐ and feel free to fork or suggest improvements!
