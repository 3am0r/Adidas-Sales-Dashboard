# Adidas-Sales-Dashboard

<!-- Demo GIF -->
<p align="center">
  <img src="demo.gif" alt="Adidas Sales Dashboard Demo" width="100%" />
</p>

# 👟 Adidas Sales Dashboard – Power BI Project

Welcome to my interactive **Adidas Sales Dashboard**, built using **Power BI** to uncover actionable business insights from Adidas' sales data. This project demonstrates advanced data modeling, DAX measures, and impactful visual storytelling.

---

## 📌 Project Overview

This dashboard provides a clear overview of Adidas sales performance across regions, retailers, and sales channels. It helps stakeholders quickly identify top-selling products, profitable areas, and overall business trends.

🔧 **Tools Used:**
- Power BI 💡
- Power Query ⚙️
- DAX 📊

---

## 🗂️ Dashboard View Tabs

### 1️⃣ **Overview Page**
Provides a summary of the main KPIs:
- 📈 Total Sales
- 💰 Operating Profit
- 📦 Quantity Sold

---

### 2️⃣ **Retailer Performance**
- 📊 **Clustered Bar Chart** showing total sales by retailer.
- Identify high-performing distribution partners.

---

### 3️⃣ **Regional Sales**
- 🌍 **Stacked Column Chart** showing total sales by region.
- 🗺️ **Map Visual** displaying sales distribution across states.
- 🎯 Highlights **Top 5 Cities & States**.

---

### 4️⃣ **Sales Channels**
- 🧁 **Donut Chart** comparing total sales by method:
  - In-Store 🏬
  - Online 🛒
  - Outlet 🏷️
- Understand channel performance and customer preferences.

---

### 5️⃣ **Product Categories**
- 🛍️ **Clustered Bar Chart** to show top-performing product categories.
- Optimize product strategy and inventory.

---

## 📐 DAX Measures Used

- `Total Sales = SUM(Sales[SalesAmount])`
- `Operating Profit = [Total Sales] - SUM(Costs[TotalCost])`
- `Quantity Sold = SUM(Sales[Quantity])`

These DAX measures power the visual KPIs on the dashboard.

---

## 🧹 Data Preparation

Data was transformed and cleaned using **Power Query**:
- Removed nulls and duplicates
- Ensured proper data types
- Built relationships between dimension and fact tables

---
