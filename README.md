# 🍕 Pizza Sales Performance Dashboard

### 🎯 Business Problem
A pizza restaurant had a full year of raw transaction data but no visibility into which products, times, or days actually drove revenue — making it hard to plan staffing, inventory, and promotions with any confidence.

### ✅ Solution
Built an end-to-end analysis pipeline: validated KPIs in SQL first, then rebuilt them as DAX measures in an interactive Power BI dashboard, so stakeholders can filter by time, category, and size to make staffing and inventory decisions on demand.

### 🛠 Tools & Techniques
`MySQL` `Power BI` `DAX` `Power Query` 
— KPI querying & validation, star-schema data modeling (Date + Time dimension tables), DAX measures, Power Query data cleaning, interactive slicers & dynamic charts.

### 📊 Dataset
One full year of transactional order data — Order Details ID, Order ID, Pizza ID, Quantity, Order Date, Order Time, Unit Price, Total Price, Pizza Size, Pizza Category, Ingredients, and Pizza Name.

### 🔍 Key Findings
- Classic category pizzas drive the highest revenue; Classic Deluxe is the top seller
- Medium and Large sizes contribute the most sales
- Orders peak in the afternoon/evening, reaching ~3,000 orders at peak hour
- Weekdays outsell weekends; sales peak mid-year (May, July)

---

### 📄 Project Files

📋 **Detailed documentation:** [View Project Report](https://github.com/monalisa-analytics/Pizza-Sales-Analysis-Dashboard/blob/main/Report/README.md)
🗄 **SQL Queries:** [Sql query](https://github.com/monalisa-analytics/Pizza-Sales-Analysis-Dashboard/blob/main/SQL/SQL_Query.SQL)
📊 **Power BI DAX:** [View DAX File](https://github.com/monalisa-analytics/Pizza-Sales-Analysis-Dashboard/blob/main/PowerBI/Dax_Formula) &nbsp;|&nbsp; 📁 [Download the .pbix file](https://github.com/monalisa-analytics/Pizza-Sales-Analysis-Dashboard/raw/main/PowerBI/pizza%20sales%20power%20bi%20dashboard%20%282%29.pbix)




