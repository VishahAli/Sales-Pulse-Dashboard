Sales Pulse – Interactive Sales Analytics Dashboard

An interactive Power BI dashboard developed to analyze sales performance, monitor key business KPIs, identify sales patterns, and support data-driven business decision-making.

1. Project Overview

Sales Pulse is a Business Intelligence and Data Analytics project developed using Microsoft Power BI.

The project focuses on cleaning, transforming, analyzing, and visualizing sales data to create an interactive dashboard for business performance analysis.

The dashboard helps users:

Monitor overall sales performance
Track important business KPIs
Analyze sales trends over time
Compare sales across regions
Analyze product categories and sub-categories
Understand customer segment performance
Compare different shipping modes
Identify top-performing products
Explore sales data through interactive filters

The dashboard converts raw sales data into a clear and interactive business reporting solution.

2. Technology Stack
Technology	Purpose
Microsoft Power BI	Dashboard Development and Data Visualization
Power Query	Data Cleaning and Transformation
DAX	KPI Calculations and Measures
Excel	Dataset Source
Power BI Visuals	Business Performance Analysis
3. Data Source

This project uses the Superstore Sales Dataset available on Kaggle.

Dataset Website:

Superstore Sales Dataset – Kaggle

Dataset Download:

View and Download Dataset

Dataset Information

The dataset contains sales and order information including:

Order Date
Ship Date
Ship Mode
Customer ID
Customer Name
Customer Segment
Country
City
State
Postal Code
Region
Product ID
Category
Sub-Category
Product Name
Sales
4. Data Cleaning and Preparation

The dataset was prepared using Power Query before developing the dashboard.

The main preparation steps included:

Checked column names and data structure
Corrected data types
Converted Order Date to Date format
Converted Ship Date to Date format
Converted Sales to Decimal Number
Converted Postal Code to Text
Checked column quality
Checked for missing values
Reviewed categorical fields for consistency
Preserved multiple records associated with the same Order ID

Note: Duplicate Order IDs were not removed because a single order can contain multiple products and therefore appear across multiple rows.

5. DAX Measures

The dashboard uses DAX measures to calculate important business KPIs.

Total Sales
Total Sales = SUM('Sales Pulse'[Sales])
Total Orders
Total Orders = DISTINCTCOUNT('Sales Pulse'[Order ID])
Total Customers
Total Customers = DISTINCTCOUNT('Sales Pulse'[Customer ID])
Average Order Value
Average Order Value =
DIVIDE(
    [Total Sales],
    [Total Orders]
)
6. Dashboard Features and Highlights
KPI Analysis

The dashboard provides four key performance indicators:

Total Sales
Total Orders
Total Customers
Average Order Value

These KPIs provide a quick overview of overall sales performance.

Sales Trend Analysis

A time-based visualization is used to analyze changes in sales performance over time.

The analysis includes:

Sales trends over time
Identification of sales fluctuations
Time-based performance analysis
Product and Category Analysis

The dashboard analyzes sales performance across different product categories and products.

The analysis includes:

Category-wise sales
Product-level sales analysis
Top 10 products by sales
Comparison of product performance
Regional Analysis

Sales performance is analyzed across four regions:

Central
East
South
West

This allows users to compare regional contributions to overall sales.

Customer Segment Analysis

Sales performance is analyzed across:

Consumer
Corporate
Home Office

This helps identify the contribution of different customer segments.

Shipping Analysis

The dashboard analyzes sales associated with different shipping modes:

Standard Class
Second Class
First Class
Same Day
7. Interactive Features

The dashboard includes interactive slicers for:

Year
Region
Category
Segment

Users can select different filters to dynamically explore the sales data.

The dashboard also supports cross-visual interactions, allowing selections in one visual to affect related visuals.

8. Dashboard Visualizations
KPI Cards
Total Sales
Total Orders
Total Customers
Average Order Value
Charts
Sales Trend Over Time
Sales by Category
Sales by Region
Sales by Customer Segment
Sales by Ship Mode
Top 10 Products by Sales
9. Business Insights

The dashboard can be used to identify:

Overall sales performance
Sales trends over time
High-performing product categories
Top-selling products
Strong-performing regions
Customer segment contribution
Shipping mode performance

These insights can support data-driven business analysis and decision-making.

10. Project Outcome

This project demonstrates the practical application of Microsoft Power BI for business data analysis and visualization.

Through this project, I developed hands-on experience in:

Power BI Dashboard Development
Power Query Data Transformation
DAX Measures
Data Visualization
KPI Development
Business Data Analysis
Interactive Reporting
Business Intelligence

The final dashboard transforms raw sales data into an interactive reporting solution that makes sales performance easier to understand, compare, and analyze.

11. Project Repository

The complete project is available on GitHub:

Sales Pulse – GitHub Repository

The repository contains the Power BI template, dataset, dashboard previews, and project documentation.

12. Project Structure
Sales-Pulse-Dashboard/
│
├── README.md
├── SALES PULSE DASHBOARD (1).pbit
├── Sales Pulse Dashboard 2 jpj
├── Sales Pulse Dashboard jpj
└── Sales Pulse Data Set.xlsx
13. Data Source and Credit

Dataset: Superstore Sales Dataset

Source: Kaggle

Dataset Author: Rohit Sahoo

Dataset Website:

Superstore Sales Dataset – Kaggle

This project is an independent Power BI dashboard implementation using the publicly available dataset.

14. Author
Vishah Ali

BBA Student | Business Analytics and Data Visualization Enthusiast

Skills Demonstrated
Microsoft Power BI
Power Query
DAX
Data Visualization
Business Analytics
Excel
Business Intelligence
Project Links

GitHub Repository:

Sales Pulse – Interactive Sales Analytics Dashboard

Dataset:

Superstore Sales Dataset – Kaggle
