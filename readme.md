# 📊 Sales Analytics Dashboard - Power BI

## 📝 Overview
This Power BI project is a comprehensive **Sales Analytics Dashboard** designed to provide deep insights into overall sales performance, customer behavior, and product trends. The report consists of interactive visuals and drillthrough pages to allow users to explore metrics in detail.

## 🕐 Time Taken
> ⏳ **Total Duration**: ~10-12 hours spread over 2 days  
This includes data cleaning, modeling, DAX measures, visuals creation, drillthrough design, and layout polish.

---

## 📁 Report Pages

### 1️⃣ **Main Dashboard**
- 💡 High-level KPIs: Total Sales, Returns, Profit
- 📈 Visuals:
  - Clustered Bar: Sales by Product Category
  - Donut Chart: Sales Share by Region
  - Line Chart: Sales Trend over Time
  - Table: Detailed transactions

### 2️⃣ **Product Detail Page**
- 🎯 Drillthrough-enabled
- 🚀 Visuals:
  - KPI Cards: Sales, Units Sold, Return Count
  - Line Chart: Monthly Sales Trend
  - Table: Transactions filtered by selected product

### 3️⃣ **Customer Detail Page**
- 🧑 Focus on individual customers
- 💬 Visuals:
  - KPI Cards: Total Sales, Avg Purchase, Return Rate
  - Line Chart: Customer Purchase Timeline
  - Table: Purchase History

---

## 🔧 Key Work Done

### ✅ **Data Modeling**
- Connected multiple tables: `Sales`, `Products`, `Customers`, `Returns`
- Defined relationships and cleaned tables using **Power Query Editor**

### ✅ **DAX Measures**
- Created custom measures for:
  - `Total Sales`
  - `Total Units`
  - `Total Returns`
  - `Sales MoM`, `YTD Sales`
  - `Customer Purchase Count`, `Return Rate`
- Calculated KPIs for both summary and drillthrough contexts

### ✅ **Drillthrough Setup**
- Enabled detailed filtering from main visuals into **Product** and **Customer** pages
- Passed values using `Drillthrough Fields` like `Product Name` and `Customer ID`

### ✅ **Visual Design**
- Followed a consistent theme across all pages
- Used contrasting card backgrounds and readable color palette
- Icons and slicers for filtering by date, region, and category

---

## 🛠️ Tools Used
- **Microsoft Power BI Desktop**
- **Power Query Editor**
- **DAX (Data Analysis Expressions)**
- Visual customizations using standard Power BI visuals

---

## 🚀 How to Use
1. Open the `.pbix` file using Power BI Desktop
2. Explore the **Main Dashboard**
3. Right-click on a product or customer to drill into details
4. Use slicers to filter data by date, region, or category

---

## ✨ Future Improvements
- Add Forecasting visual using built-in analytics
- Integrate budget vs. actual comparison
- Enhance performance with optimized data model

---

## 🤝 Credits
Created by **Dev** | Data Analytics Enthusiast  
