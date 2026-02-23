# 📄 Pizza Sales Performance Dashboard – Project Report

**Prepared by:** Monalisa Mahanta  
**Date:** 14 January 2026  

---

## 🛠 Tools Used
- Power BI  
- MySQL  
- Microsoft Excel  
- DAX  
- Power Query  

---

## 1️⃣ Introduction
This project focuses on analyzing pizza sales data to evaluate business performance, customer purchasing behaviour, and operational efficiency.  

The analysis was performed using **MySQL** for data extraction and KPI validation, and **Power BI** for data modeling, visualization, and dashboard development.

Key Performance Indicators (KPIs) such as **Total Revenue**, **Total Orders**, **Total Pizzas Sold**, **Average Order Value**, **Average Pizzas per Order**, **Peak Ordering Hour**, and **Revenue Contribution by Pizza Size & Category** were calculated using SQL queries and recreated using DAX measures in Power BI to ensure consistency and accuracy.

An interactive Power BI dashboard was designed using slicers, KPI cards, and dynamic charts, allowing users to explore sales performance by time, category, and size. This dashboard enables stakeholders to identify growth opportunities, optimize staffing during peak hours, and make informed data-driven decisions.

---

## 2️⃣ Objectives
- Analyze total revenue and total orders  
- Identify best and worst performing pizza categories and sizes  
- Understand customer peak order times and days to optimize workforce planning  
- Track monthly sales trends  
- Analyze seat efficiency in the store  

---

## 3️⃣ Dataset Description
The dataset contains transactional sales data for one full year with the following fields:

- Order Details ID  
- Order ID  
- Pizza ID  
- Quantity  
- Order Date  
- Order Time  
- Unit Price  
- Total Price  
- Pizza Size  
- Pizza Category  
- Pizza Ingredients  
- Pizza Name  

---

## 4️⃣ Tools & Technologies
- **Excel:** Data cleaning  
- **MySQL:** Querying data and KPI calculation  
- **Power BI:** Data modeling and dashboard creation  
- **DAX:** Creating calculated measures  
- **Power Query:** Data cleaning and transformation  

---

## 5️⃣ Data Cleaning & Preparation
- Removed null and duplicate records  
- Converted date and time data types  
- Created pizza sales table in MySQL and imported data  
- Created a Date table in Power BI for month-based analysis  
- Created a Time table for hourly order analysis  
- Standardized pizza category and size values  

---

## 6️⃣ Key Performance Indicators (KPIs)
- Total Revenue  
- Total Orders  
- Total Pizzas Sold  
- Average Order Value  
- Average Pizzas per Order  
- Seat Utilization %  
- Peak Hour Orders  
- Top Selling Pizza  

> Separate documents were created detailing KPI calculations using **MySQL queries** and **Power BI DAX measures**.

---

## 7️⃣ Dashboard Explanation
The dashboard includes:
- KPI cards summarizing business performance  
- Pie charts showing Total Orders and Revenue by Day  
- Line chart for monthly revenue trends  
- Bar charts for category-wise and hourly sales  
- Interactive slicers for pizza size and category  

---

## 8️⃣ Key Insights
- Most orders are placed during afternoon and evening hours  
- Classic category pizzas generate the highest revenue  
- **Classic Deluxe Pizza** is the top-selling product  
- Medium and Large size pizzas contribute the highest sales  
- Weekdays have more orders than weekends  
- Sales peak during mid-year months, especially **May and July**  
- Highest peak-hour order volume is approximately **3,000 orders**  

---

## 9️⃣ Challenges Faced
- Creating accurate Date and Time dimension tables  
- Writing correct MySQL queries and DAX formulas for KPIs  
- Designing a clean, user-friendly dashboard layout  
- Managing relationships between multiple tables  

---

## 🔚 Conclusion
This project demonstrates how raw transactional data can be transformed into meaningful business insights using SQL and Power BI. KPI calculations were validated in MySQL to ensure data accuracy before visualization.

In Power BI, the data model followed a star schema with Date and Time dimension tables, enabling flexible time-based analysis and improved performance. DAX measures allowed dynamic KPI calculations with real-time filtering.

The dashboard provides visibility into sales trends, customer ordering behavior, peak business hours, and product performance, supporting data-driven decisions related to staffing, inventory planning, promotions, and revenue growth.

---

## 🚀 Future Scope
- **Profitability Analysis:** Include cost data to calculate profit margins  
- **Customer Analytics:** Analyze repeat purchases and customer lifetime value  
- **Sales Forecasting:** Implement time-series forecasting  
- **Geographical Analysis:** Evaluate performance by location or region  
- **Automation:** Enable live database connections for real-time reporting  
- **Advanced Interactivity:** Add drill-throughs, tooltips, and what-if analysis  
- **Data Security:** Implement role-level security and access control  
