# 🍕 Pizza Sales Analysis Dashboard

This repository contains the SQL scripts and Power BI visualizations used to analyze pizza sales performance across categories, sizes, and time dimensions. The project demonstrates how to transform raw transactional data into actionable insights using SQL and Power BI.

## 📊 Overview

- Total Orders: 21,350
- Total Revenue: $817,860
- Total Pizzas Sold: 49,574
- Avg. Order Value: $38.31
- Avg. Pizzas per Order: 2.32

## 🛠️ Tech Stack

- **SQL Server**: Data modeling, view creation
- **Power BI**: Interactive dashboards and visualizations
- **GitHub**: Version control and collaboration

## 📁 Folder Structure

## 🧠 SQL Views

The following views were created to support Power BI visualizations:

- `vw_order_summary`: Aggregates order count, revenue, and average metrics
- `vw_category_sales`: Breaks down sales by pizza category
- `vw_size_revenue`: Revenue distribution by pizza size
- `vw_top_bottom_items`: Identifies best and worst performing pizzas
- `vw_weekday_monthly_orders`: Tracks order trends by weekday and month

Each view is optimized for direct import into Power BI using native connectors.

## 📈 Power BI Visuals

The dashboard includes:

- **Overview KPIs**: Orders, Revenue, Avg. Price, Avg. Quantity
- **Weekday Trends**: Bar chart of orders by day
- **Category & Size Analysis**: Revenue and quantity breakdowns
- **Monthly Orders**: Seasonality insights
- **Top & Bottom Performers**: Revenue and order volume comparisons

- ## 📸 Dashboard Screenshots

Here are some sample views from the Power BI dashboard:

### 1. Overview Metrics
![Pizza Sales Overview](https://github.com/ShadySaad2001/PIzza-Sales-Analysis-Sql-Power-bi-/blob/main/Pizza%201.png)

### 2. Category & Size Analysis
![Pizza Sales Overview](https://github.com/ShadySaad2001/PIzza-Sales-Analysis-Sql-Power-bi-/blob/main/Pizza%202.png)

### 3. Monthly & Product Performance
![Pizza Sales Overview](https://github.com/ShadySaad2001/PIzza-Sales-Analysis-Sql-Power-bi-/blob/main/Pizza%203.png)

## 🚀 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/pizza-sales-analysis.git
