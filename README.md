# Pizza Sales Analytics Dashboard

## Overview

This project presents a **Pizza Sales Analytics Dashboard** that combines **Excel** and **SQL Server** to analyze pizza sales data. The dashboard tracks key performance indicators (KPIs) and provides insights into sales trends. SQL queries are used to replicate the same analytics and results as in Excel, ensuring consistency across both platforms.

## Features

* **KPIs Analyzed:**

  * **Total Revenue**
  * **Average Order Value**
  * **Total Orders**
  * **Total Pizzas Sold**
  * **Average Pizzas per Order**

* **SQL Queries:**

  * SQL queries are written to replicate the results found in Excel. The SQL Server database contains the raw data.
  
* **Excel Data Processing:**

  * Power Query is used in Excel to clean and transform the raw data (e.g., changing pizza sizes from "R" to "Regular" and extracting the **Order Day** from the **Order Date**).
  * Calculations for total revenue, average order value, total pizzas sold, and average pizzas per order are carried out in Excel.

* **Charts & Visualizations:**

  * **Daily Orders Trend:**
  * **Hourly Orders Trend:** 
  * **Pizza Category Sales Breakdown:** 
  * **Pizza Size Sales Breakdown:**
  * **Top 5 Best Sellers & Bottom 5 Worst Sellers:**
  * 
## Insights

* **Pizza Category Breakdown:**

  * The **Classic Deluxe** pizza is the best seller.
  * The **Brie Carre** pizza is the worst seller.

* **Pizza Size Breakdown:**

  * Large pizzas contribute to the highest sales percentage.

* **Sales Trends:**

  * Orders are highest on **Friday** and **Saturday**, allowing businesses to focus on these peak days for promotions and staffing.
  * The **Hourly Trend Chart** shows that certain hours of the day drive higher sales, helping businesses optimize marketing and delivery strategies.

## How It Works

1. **SQL Server:**

   * The raw sales data is stored in **SQL Server**.
   * SQL queries are used to retrieve the necessary data and generates identical results to those produced in Excel.

2. **Excel:**

   * Power Query is used in Excel to connect to the SQL Server database and import the data.
   * The data is processed and cleaned in Excel (e.g., changing "R" to "Regular" and extracting the **Order Day** from the **Order Date** using Power Query).
   * PivotTables and charts are created to visualize the key metrics such as sales trends, top sellers, and pizza category sales.


### **Efficiency and Time-Saving**

* The project automates the retrieval and analysis of sales data, reducing the manual effort required to generate reports.
* The dashboard provides real-time insights by connecting directly to the SQL Server database and updating visualizations in Excel automatically.


### **Actionable Insights**

* **Top Sellers:** The analysis shows that **Classic Deluxe** pizzas are the most popular, while **Brie Carre** pizzas underperform. This helps businesses decide whether to remove or promote certain pizzas.
* **Sales by Pizza Size:** Larger pizzas have a higher sales percentage, which can influence inventory decisions and promotions focused on upsizing orders.
* **Hourly & Daily Trends:** By analyzing when customers are placing orders, businesses can optimize staffing and marketing efforts during peak hours and days.

---


