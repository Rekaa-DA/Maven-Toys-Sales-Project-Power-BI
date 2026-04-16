# 📊 Maven Toys Sales & Inventory Analysis Dashboard

## 🧩 Project Overview
This project analyzes **Maven Toys sales and inventory data** by integrating multiple data sources into a structured data model.  
It focuses on understanding **sales performance, demand patterns, inventory efficiency, and profitability** to support better data-driven decision-making.

The project is developed using **Excel for data preparation** and **Power BI for modeling and visualization**.

## 🎯 Objectives
- Analyze sales trends and business growth over time  
- Understand product demand and its impact on inventory  
- Identify gaps between sales and available stock  
- Evaluate store performance and identify top and underperforming stores  
- Improve inventory utilization and track stock movement  
- Analyze profitability using cost, price, and sales  
- Identify key patterns influencing overall business performance  

## ❗ Problem Statement
Maven Toys lacks a centralized analytics system to track sales, product demand, store performance, and inventory across its operations.

This results in:
- Limited visibility into business performance  
- Difficulty identifying trends and inefficiencies  
- Poor inventory planning and decision-making challenges  

This project solves these issues by building a **structured data model and interactive dashboard system** for clear business insights.

## 🛠 Tools & Technologies
- **Excel** – Data cleaning, transformation, validation, and calculations  
- **Power BI** – Data modeling, DAX measures, and interactive dashboard creation  

## 🔄 Data Transformation (Excel / Power Query)
- Removed duplicate records to ensure data accuracy  
- Standardized column names and formatting  
- Cleaned text fields (removed extra spaces and special characters)  
- Corrected data types (Date, Number, Currency)  
- Created calculated columns (Profit, Profit Margin)  
- Handled missing/null values  
- Validated data consistency across all tables  

## 🏗 Data Model
- Star schema design implemented  
- Fact Table: **Sales**  
- Dimension Tables: **Products, Stores, Inventory**  
- One-to-many relationships established  
- Single-direction filtering used for performance optimization  

## 📐 Calculated Columns
- Profit = Sales - Cost  
- Profit Margin (%) = Profit / Sales  

## 📊 DAX Measures
- Total Sales  
- Total Units Sold  
- Total Profit  
- Profit Margin  
- Month-over-Month (MoM) Growth  
- Total Stock  
- Growth Percentage  
- Dynamic Titles (Sales / Store views)  

## 📈 Dashboard Visualizations

- **KPI Cards** – Total Sales, Profit, Units Sold, Profit Margin, MoM Growth  
- **Bar Charts** – Product, store, and category performance comparison  
- **Line Charts** – Sales and profit trends over time  
- **Pie & Donut Charts** – Revenue distribution by category and stores  
- **Tree Map** – Stock distribution by product  
- **Ribbon Chart** – Ranking changes across products  
- **Map Visualization** – Store-wise sales distribution  
- **Waterfall Chart** – Profit contribution by products  
- **Gauge Chart** – Actual vs Target sales comparison  
- **Slicers** – Interactive filtering (date-based)  
- **Bookmarks & Buttons** – Toggle between All Products and Top 5 Products view  
- **Top N Filter** – Highlight top-performing products dynamically

## 🔍 Key Insights

### 📌 Descriptive Insights
- Total Sales: **$7.48M**, Units Sold: **549K**, Profit: **$2.18M**  
- Top Product: **Lego Bricks ($1.33M)**  
- Weak Products: **Uno Card Game, Mr. Potato Head**  
- Top Category: **Toys ($2.78M)**  
- Best Store: **Ciudad de Mexico 2 ($293K)**  
- Peak Sales Month: **December ($877K)**  
- Low Sales Month: **August ($489K)**  

### 📌 Diagnostic Insights
- Strong dependency on Toys and Electronics (~66% revenue share)  
- Seasonal demand drives December peak  
- Inventory mismatch observed (overstock & understock issues)  
- Sales gap of **$748K (90.9% target achievement)**

### 📌 Predictive Insights
- Sales expected to reach **~$8.23M in future cycles**  
- Q4 likely to remain strongest period  
- Weak products expected to continue underperforming  
- Inventory imbalance may persist if not corrected  

### 📌 Prescriptive Insights
- Focus marketing on **Lego Bricks & Colorbuds**  
- Improve weak products via bundling and discounts  
- Diversify revenue beyond Toys & Electronics  
- Optimize inventory (reduce overstock, fix stockouts)  
- Target seasonal dips with promotional campaigns  

## 📌 Conclusion
The analysis shows strong overall business performance with **steady growth and profitability**, but also highlights key risks:

- Heavy reliance on few products and categories  
- Clear seasonal sales dependency  
- Inventory imbalance issues  
- Small but important revenue gap to target  

By improving **product diversification, inventory management, and seasonal strategy**, Maven Toys can further enhance growth and efficiency.

📄 Report Structure

This project is delivered as a 4-page analytical report built in Power BI, designed to provide both detailed analysis and interactive insights.

