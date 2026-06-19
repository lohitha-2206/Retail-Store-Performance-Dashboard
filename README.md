# 🛒 Retail Store Performance Dashboard

An end-to-end Power BI dashboard project built using a Retail Sales dataset to analyze business performance across revenue, profit, customers, products, stores, and time intelligence metrics.

This project demonstrates advanced Power BI skills including data cleaning, data modeling, DAX measures, calculated columns, ranking functions, filtering functions, time intelligence, and dashboard design.

---

## 📌 Project Overview

The objective of this project is to provide business insights into:

- Revenue Performance
- Profitability Analysis
- Customer Analytics
- Product Performance
- Store Performance
- Time Intelligence Metrics

The dashboard enables decision-makers to monitor KPIs and identify trends through interactive visualizations.

---

## 🛠 Tools & Technologies

- Power BI
- DAX
- Power Query
- Data Modeling
- Excel

---

## 📊 Dataset Information

The project uses a retail sales dataset consisting of 5 tables:

### Fact_Sales (500 Records)

Contains transactional sales data:

- Invoice
- Date
- Customer_ID
- Product_ID
- Store
- City
- Quantity Sold (Qty)
- Price
- Cost
- Discount
- Revenue

### Dim_Customer (100 Records)

Contains customer-related information:

- Customer_ID
- Customer_Name
- Segment (Gold, Silver, Platinum)
- City
- Region

### Dim_Product (20 Records)

Contains product-related information:

- Product_ID
- Product Name
- Product Category

### Calendar Table (730 Records)

Used for Time Intelligence calculations:

- Date
- Year
- Month
- Month Number
- Quarter

### Capstone Assignments Table

Contains 60 business questions used to implement DAX concepts and business calculations.

---

## 🏗 Data Model

A Star Schema data model was implemented:

Dim_Customer (1) ───── (*) Fact_Sales

Dim_Product (1) ───── (*) Fact_Sales

Calendar (1) ───── (*) Fact_Sales

This model enables efficient filtering, aggregation, and advanced DAX calculations.

## 🧹 Data Preparation

Performed data cleaning and transformation using Power Query:

- Removed duplicate records
- Checked missing values
- Corrected data types
- Created Date Table
- Established relationships between tables

---

## ⭐ DAX Concepts Implemented

### Aggregation Functions

- SUM()
- COUNT()
- DISTINCTCOUNT()
- COUNTROWS()

### Iterator Functions

- SUMX()

### Filter Functions

- CALCULATE()
- FILTER()
- ALL()

### Ranking Functions

- RANKX()

### Table Functions

- TOPN()
- SUMMARIZE()
- UNION()

### Relationship Functions

- RELATED()
- RELATEDTABLE()

### Dynamic Functions

- SELECTEDVALUE()
- SWITCH()
- DIVIDE()

### Time Intelligence

- Running Total Sales
- Rolling 3 Month Sales
- Moving Average
- Year-To-Date Revenue
- Same Period Last Year Revenue

---

## 📈 Dashboard Pages

### 1️⃣ Executive KPI Dashboard

KPIs:

- Total Revenue
- Total Profit
- Total Customers
- Margin %

Visuals:

- Revenue by City
- Revenue by Category
- Monthly Revenue Trend
- Revenue by Store

---

### 2️⃣ Product Performance Dashboard

KPIs:

- Total Profit
- Total Orders
- Total Quantity Sold
- Average Order Value

Visuals:

- Top Products by Revenue
- Monthly Sales vs Profit Trend
- Monthly Orders Trend
- Top Products by Quantity Sold

---

### 3️⃣ Customer Analytics Dashboard

KPIs:

- Total Customers
- Total Transactions

Visuals:

- Monthly Customer Trend
- Top Customers by Revenue
- Revenue by Customer Segment
- Top Customers by Transactions

---

### 4️⃣ Time Intelligence Dashboard

Metrics:

- Current MTD Sales
- Current QTD Sales
- Current YTD Sales

- Previous MTD Sales
- Previous QTD Sales
- Previous YTD Sales

- Same Period Last Year MTD Sales
- Same Period Last Year QTD Sales
- Same Period Last Year YTD Sales

---

## 📌 Key Insights

- Dubai generated the highest revenue contribution.
- Furniture category recorded the highest sales.
- Revenue showed a strong upward trend towards year-end.
- Platinum customer segment generated the highest revenue.
- Certain products significantly outperformed others in revenue and quantity sold.

---

## 📂 Repository Structure

Retail-Store-Performance-Dashboard/

│

├── Dataset/

│ └── Retail_Dataset.xlsx

│

├── PowerBI/

│ └── Retail_Dashboard.pbix

│

├── Screenshots/

│ ├── Executive_KPI.png

│ ├── Product_Performance.png

│ ├── Customer_Analytics.png

│ └── Time_Intelligence.png

│

└── README.md

---

## 👩‍💻 Author

Lohitha Savvana

Final Year B.Tech Student

Skills:
SQL | Power BI | Python | Excel | Data Analytics
