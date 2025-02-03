# Bank Muamalat Digital User Churn and Sales Dashboard

## Introduction
This project is part of the Business Intelligence Analyst Project-Based Internship at Bank Muamalat. The project involves analyzing sales data using 4 datasets (Customers, Products, Orders, and ProductCategory) to create a comprehensive sales performance dashboard. The focus is on analyzing sales trends, product performance, and geographical distribution to provide strategic insights for business growth.

## Tools Used
- Google BigQuery - for data processing and analysis
- Google Looker Studio - for dashboard visualization

## Process

### 1. Data Preparation in BigQuery
Created a master table by combining data from all four datasets with the following key fields:
- CustomerEmail (cust_email)
- CustomerCity (cust_city)
- OrderDate (order_date)
- OrderQty (order_qty)
- ProductName (product_name)
- ProductPrice (product_price)
- ProductCategoryName (category_name)
- TotalSales (total_sales)

### 2. Data Relationships Identified
- Customer to Orders: CustomerID
- ProductCategory to Products: CategoryID
- Orders to Products: ProdNumber

### 3. Dashboard Creation
Using the master table, created a dashboard in Google Looker Studio that visualizes:
- Total Sales Performance (1,754,750.57)
- Total Goods Sold (11,654)
- Sales Distribution by City
- Product Category Analysis
- Sales Trends Over Time (2020-2021)

## Results
The final dashboard can be accessed [here](https://lookerstudio.google.com/reporting/a5164c6c-68e5-4d2d-9535-018b94d451ca).

### Key Insights:
1. Top Performing Products:
   - Robots (743,505 in sales)
   - Drones (477,447 in sales)

2. Highest Quantity Sales:
   - eBooks (3,123 units)
   - Training Videos (2,081 units)

3. Strategic Recommendations:
   - Maintain Sales:
     - Focus on optimizing flagship products (Robots & Drones)
     - Implement seasonal sales management
     - Strengthen existing market areas

   - Increase Sales:
     - Develop cross-selling strategies
     - Expand into strategic new territories
     - Optimize digital product offerings

## Contact
For any questions or feedback about this project, please reach out:
- LinkedIn: Saila Fikriyya
- GitHub: https://github.com/sailafs/Rakamin-BM-Analytics
