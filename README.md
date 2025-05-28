# Sales-Tableau-Project

## 🏢 Project Background

This project simulates a retail business operating in the consumer goods sector. The company operates across various regions and product categories, with a primary business model focused on direct B2C (business-to-consumer) sales. As a data analyst, the objective is to understand key sales metrics, analyze trends across different dimensions (e.g., regions, categories), and derive insights to support data-driven decision-making.

The project leverages Excel data cleaning, SQL-based data analysis, and Tableau for data visualization to deliver a clear, concise, and actionable sales performance report.

Insights and recommendations are provided on the following key areas:

• Sales Performance Analysis: Overall sales, profit, and quantity trends.  
• Customer Behavior Analysis: Customer acquisition, order frequency, and top customer segments.  
• Product Performance Analysis: Sales and profitability by product sub-category.  
• Geographic Sales Distribution: Sales and customer insights across different regions.  

Interactive Tableau dashboards used to report and explore sales trends can be found here [https://public.tableau.com/views/SalesDashBoard_17482321345940/SalesDashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]

## 🧱 About The Dataset

This dataset contains 4 tables in CSV format.    
•	**Customers table** : Customer ID, Customer Name  
•	**Location table** : Postal Code, City, State, Region, Country/Region  
•	**Orders table** : Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Segment, Postal Code, Product ID, Sales, Quantity, Discount, Profit  
•	**Products table** : Product ID, Category, Sub-Category, Product Name	    

After analysing, we come to know that there is 1 Fact table and 3 Dimension tables.  
• Fact Table – Orders (it contain id, date and lot of measures)  
• Dimension Table – Customers, Location, Products  

![ER Diagram](https://github.com/aman-theanalyst/Sales-Tableau-Project/blob/main/ER-Diagram.png)


## Requirements

### Sales Dashboard 

### Dashboard Purpose  
The purpose of sales dashboard is to present an overview of the sales metrics and trends in order to analyse year-over-year sales performance and understand sales trends.  

Key Requirements are :

#### KPI Overview
Display a summary of total sales, profits and quantity for the current year and the previous year.  

#### Sales Trends
 – Present the data for each KPI on a monthly basis for both the current year and the previous year.
 – Identify months with highest and lowest sales and make them easy to recognize.
 
#### Product Subcategory Comparison
 – Compare sales performance by different product subcategories for the current year and the previous year.
 – Include a comparison of sales with profit.
 
#### Weekly Trends for Sales & Profit
 – Present weekly sales and profit data for the current year.
 – Display the average weekly values.
 – Highlight weeks that are above and below the average to draw attention to sales & profit performance.  

________________________________________

### Customer Dashboard  

### Dashboard Purpose
The customer dashboard aims to provide an overview of customer data, trends and behaviors. It will help marketing teams and management to understand customer segments and improve customer satisfaction.  
Key Requirements are :
#### KPI Overview
Display a summary of total number of customers , total sales per customer and total number of orders for the current year and the previous year.

#### Customer Trends
 – Present the data for each KPI on a monthly basis for both the current year and the previous year.
 – Identify months with highest and lowest sales and make them easy to recognize.
 
#### Customer Distribution by Number of Orders
Represent the distribution of customers based on the number of orders they have placed to provide insights into customer behavior, loyalty and engagement.

#### Top 10 Customers by Profit
 – Present the top 10 customers who have generated the highest profits for the company.
 – Show additional information like rank, number of orders, current sales, current profit and the last order date.

________________________________________

### Design & Interactivity Requirements
#### Dashboard Dynamic
 – The Dashboard should allow users to check historical data by offering them the flexibility to select any desired year.
 – Provide users with the ability to navigate between the dashboards easily.
 – Make the charts and graphs interactive, enabling users to filter data using the charts.  
 
####Data Filters  
Allow users to filter data by product information like category and subcategory and by location information like region, state and city.


## KPI's

1. Total Sales
2. Total Profit
3. Total Quantity
4. Total Customer
5. Total Orders
6. Total Sales per Customer

These KPI's are linked to the Filter which include Years(2020 -2023), Product Category and Sub Category, Location (Region, States & City).

## 💡 Executive Summary

### 🔍 Overview of Findings

The following three insights are most critical:  

1. West and Central regions generate the highest sales, but also show significant returns. More targeted strategies could optimize performance.  
2. Office Supplies is the fastest-growing category in terms of sales growth across years.  
3. Certain sub-categories, like Binders and Chairs, experience disproportionately high return rates, impacting profit margins.

### 📈 Insights Deep Dive

#### 🍿 Category & Sub-category Trends

• Best-selling category: Technology  
• High-volume sub-categories: Phones and Chairs  
• High-profit sub-categories: Copiers, Accessories and Paper  
• Sub-Category Always in Loss: Tables  
• Trend in Customer: No. of customer is maximum in 4th quater of the year  

#### 🗓️ Time-based Trends

• Peak sales months: September, October, November & December  
• Consistent sales dip: January, February   
• Year-over-year growth: Upward trend in Profit

## ✅ Recommendations:

1. Remove Tables from Sub-Category as they are always in loss.
2. Try to plan some strategies (like Discount, Provide some freebies on purchase, etc) for 1st quater of the year as the sales and toatal customer in this part of year are lowest.
3. Shift marketing and logistical resources to South and Central Region as Sales is less there.
4. Investigate return causes and adjust inventory accordingly.
5. Introduce more high-margin tech products in top-performing regions.

## DashBoard Screenshot

![DashBoard 1](https://github.com/aman-theanalyst/Sales-Tableau-Project/blob/main/Customer%20Dashboard.png)

![DashBoard 2](https://github.com/aman-theanalyst/Sales-Tableau-Project/blob/main/Sales%20Dashboard.png)

![Filter in Dashboard](https://github.com/aman-theanalyst/Sales-Tableau-Project/blob/main/Filters.png)
