# Sales Pulse – Interactive Sales Analytics Dashboard

An interactive Power BI dashboard developed to analyze sales performance, monitor key business KPIs, identify sales patterns, and support data-driven decision-making.

## 1. Project Overview

Sales Pulse is a Business Intelligence and Data Analytics project developed using Microsoft Power BI.

The project focuses on cleaning, transforming, analyzing, and visualizing sales data to create an interactive dashboard for business performance analysis.

The dashboard helps users:

- Monitor overall sales performance
- Track key business KPIs
- Analyze sales trends over time
- Compare regional sales performance
- Analyze product categories and sub-categories
- Understand customer segment performance
- Compare sales across shipping modes
- Identify top-performing products
- Explore data using interactive filters 

## 2. Technology Stack

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard Development and Data Visualization |
| Power Query | Data Cleaning and Transformation |
| DAX | KPI Calculations and Measures |
| Microsoft Excel | Dataset Source |
| Power BI Visuals | Business Performance Analysis |

## 3. Data Source

This project uses the Superstore Sales Dataset published by Rohit Sahoo on Kaggle.

**Dataset Website:**  
https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

**Dataset Download:**  
https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting?resource=download

### Dataset Fields

The dataset contains sales and order information including:

- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Postal Code
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales

## 4. Data Cleaning and Preparation

The dataset was prepared using Power Query before developing the dashboard.

The main preparation steps included:

- Checked column names and data structure
- Corrected data types
- Converted Order Date to Date format
- Converted Ship Date to Date format
- Converted Sales to Decimal Number
- Converted Postal Code to Text
- Checked column quality
- Checked for missing values
- Reviewed categorical fields for consistency
- Preserved multiple records associated with the same Order ID

**Note:** Duplicate Order IDs were not removed because a single order can contain multiple products and therefore appear across multiple rows.

## 5. DAX Measures

The dashboard uses DAX measures to calculate key business KPIs.

### Total Sales

```DAX
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
6. Dashboard Features
KPI Analysis

The dashboard includes:

Total Sales
Total Orders
Total Customers
Average Order Value
Sales Trend Analysis

The dashboard provides time-based sales analysis to identify:

Sales trends over time
Sales fluctuations
Changes in sales performance
Product and Category Analysis

The dashboard analyzes:

Category-wise sales
Product-level sales
Top 10 products by sales
Product performance comparison
Regional Analysis

Sales performance is compared across:

Central
East
South
West
Customer Segment Analysis

Sales are analyzed across:

Consumer
Corporate
Home Office
Shipping Analysis

Sales performance is analyzed across:

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

Users can apply filters to dynamically explore the sales data.

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

These insights can support business analysis and data-driven decision-making.

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

https://github.com/VishahAli/Sales-Pulse-Dashboard

The repository contains the Power BI template, dataset, dashboard files, and project documentation.

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
https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

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
Microsoft Excel
Business Intelligence
Project Links

GitHub Repository:
https://github.com/VishahAli/Sales-Pulse-Dashboard

Dataset:
https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

This project reflects my continued development in Business Analytics, Business Intelligence, and data-driven decision-making.
