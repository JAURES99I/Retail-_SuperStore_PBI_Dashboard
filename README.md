# Retail-_SuperStore_PBI_Dashboard
Retail sales analytics dashboard built with Power BI, Power Query, and DAX featuring YoY growth and KPI analysis.

# Retail Sales Analytics Dashboard (Power BI + Power Query + DAX)

## Overview
This project is an end-to-end data analytics solution built in Power BI. It transforms a raw, semi-structured CSV dataset into a clean analytical model and interactive business intelligence dashboard.

The goal is to analyze retail performance across regions, products, and time, while demonstrating data cleaning, modeling, and advanced DAX capabilities.

---

## Tech Stack
- Power BI (Data Visualization)
- Power Query (ETL / Data Cleaning)
- DAX (Measures & Time Intelligence)

---

##  Key Features

### Data Engineering (Power Query)
- Fixed misaligned CSV structure with column-level reconciliation logic
- Implemented null-fallback transformation strategy across multiple fields
- Standardized schema and corrected data types (dates, numeric fields, text fields)

### Data Modeling
- Built a structured analytical model from raw transactional data
- Created a star-schema style dataset for reporting
- Optimized relationships for time-based analysis

### DAX Measures
- Total Sales
- Total Profit
- Profit Margin
- Running Total (Sales & Profit)
- Year-over-Year (YoY) Growth %

### Dashboard Features
- KPI Cards (Sales, Profit, Margin, Orders)
- Sales by Region
- Top 10 Products by Sales
- Sales vs Profit Scatter Analysis
- Time Series Trend (Monthly Sales)
- Interactive slicers (Region, Category, Segment, Date)

---

## Key Insights
- Regional performance differences highlight uneven revenue distribution
- Certain product categories drive high sales but lower profit margins
- Seasonal trends visible through YoY and running total analysis

---

## Dashboard Preview

### 🟦 Overview Dashboard
![Dashboard Overview](images/SuperStoreBI.overview.png
)

### 📊 Sales by Region
![Region Analysis](images/SuperStore.region.analysis.png)

### 🏆 Top Products
![Top Products](images/Superstore.Top.10.Products
)

### 📈 Time Series Analysis
![Trend Analysis](images/SuperStore.TrendAnalysis.overtime.png)

---

## 📁 Project Structure
  /PowerBI
      └── retail-dashboard.pbix
  /images
      ├── dashboard-overview.png
      ├── region-analysis.png
      ├── top-products.png
      └── trend-analysis.png

---

## How to Use
1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Refresh data if needed
4. Explore dashboard using filters and slicers

---

## Skills Demonstrated
- Data Cleaning & Transformation (Power Query)
- Data Modeling
- DAX (Advanced Measures)
- Time Intelligence Analysis
- Business Insight Generation
- Dashboard Design

---

## Author : Kouabenan Jaures Adoua 
Built as part of a Business Technology Management (BTM) data analytics portfolio focusing on real-world BI workflows.


