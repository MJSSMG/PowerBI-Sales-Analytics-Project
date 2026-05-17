# Power BI Sales Analytics Dashboard

## Project Overview
This project is an interactive Power BI Sales Analytics Dashboard built using multiple CSV datasets. The dashboard provides insights into sales performance, customer behavior, product trends, return analysis, and regional revenue performance through interactive visualizations and KPI tracking.

---

## Dataset Used
The project uses the following CSV files:

- Customer Table
- Product Categories
- Product Subcategories
- Products
- Returns
- Sales 2015
- Sales 2016
- Sales 2017
- Territories

---

## Data Cleaning & Transformation
The following data transformation steps were performed in Power Query:

- Merged Sales 2015, 2016, and 2017 datasets
- Changed regional settings to English (United States)
- Converted Birthdate column from Text to Date
- Replaced "Mgmnt" with "Management" in Occupation column
- Removed "$" symbol from Annual Income column
- Converted Annual Income data type to Whole Number

---

# Dashboard Pages

## 1. Overview Dashboard
The Overview page provides a high-level business summary with the following visuals:

### KPI Cards
- Total Sales
- Total Orders
- Total Customers
- Return Percentage
- Last Month Sales
- Last Month Orders

### Visualizations
- Stacked Bar Chart for Sales by Sub-Category and Status
- Line Chart for Sales by Date
- Map Visualization for Total Sales by Country

### Interactive Table
Table includes:
- Product Name
- Total Sales
- Order Count
- Total Returns

### Slicers
- Category Name
- Gender
- Region
- Email Address
- Year Quarter

### Field Parameters
Implemented dynamic field parameters with:
- Measures: Sales, Orders, Returns
- Dimensions: Customer Name, Product Name

---

## 2. Product Details Dashboard
A drill-through feature was created from the Overview page to access detailed product-level insights.

### Features
- KPI Cards for Product Price and Product Cost
- Ribbon Chart for Total Sales by Year and Country
- Pie Chart for Sales by Marital Status
- Pie Chart for Sales by Parent Status

### Customer Details Table
Includes:
- Full Name
- Email Address
- Gender
- Parent Status
- Sum of Sales

---

## 3. Tooltip Page
A custom tooltip page was created to provide additional insights when hovering over visuals.

### Tooltip Elements
- Sub-Category Card
- Income Status Card
- Total Sales Card
- Bar Chart for Total Sales by Gender

Tooltip functionality was enabled on the Sales by Sub-Category and Status chart.

---

# Business Insights & Recommendations

## High Performing Products
- Road Bikes
- Mountain Bikes

### Recommendations
- Increase inventory
- Run promotional campaigns
- Focus marketing efforts on best-selling categories

---

## Low Performing Products
- Socks
- Cleaners
- Vests
- Caps

### Recommendations
- Offer discounts and bundle deals
- Reposition products using targeted campaigns
- Discontinue underperforming products if necessary

---

## Most Returned Products
- Water Bottle
- Patch Kit
- Mountain Tire Tube

### Recommendations
Analyze return reasons such as:
- Product quality issues
- Incorrect product descriptions
- Packaging or delivery problems

Reducing return rates can improve customer satisfaction and profitability.

---

## Top Revenue Generating Countries
- USA
- Australia
- France
- Germany
- UK

### Recommendations
- Expand operations in high-performing regions
- Increase advertising budgets
- Develop region-specific marketing strategies

---

## Customer Retention Strategies
Recommendations include:
- Loyalty programs
- Exclusive offers for returning customers
- Personalized marketing campaigns

---

## Customer Segmentation
The dashboard uses:
- Gender
- Marital Status
- Parent Status
- Income Level

### Recommendations
- Create personalized campaigns
- Improve customer engagement
- Develop targeted product recommendations

---

# Tools & Technologies Used

- Power BI
- Power Query
- DAX
- CSV Datasets

---

# Key Features

- Interactive Dashboard
- Drill-through Navigation
- Dynamic Field Parameters
- Custom Tooltips
- KPI Tracking
- Regional Sales Analysis
- Customer Segmentation
- Product Performance Analysis

---

# Conclusion
This Power BI project demonstrates a complete end-to-end business intelligence workflow including data cleaning, transformation, modeling, visualization, interactivity, and business insights generation.
