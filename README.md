# 📊 AdventureWorks Sales Analysis – Power BI Project

## 📝 Project Description

This project is an **interactive business intelligence dashboard** built using **Power BI**. It leverages the **AdventureWorks dataset**, which simulates a real-world company that sells bicycles and related products. The main objective is to provide **insights into sales performance, profitability, customer behavior, and product-level trends** to support data-driven decision-making for stakeholders.

---

## 📁 Report Pages & Detailed Features

### 1. Home Page
- Serves as the main **navigation hub** for the entire report.
- Displays **key summary metrics**:
  - Total Sales
  - Total Profit
  - Total Orders
- Filters:
  - **Year slicer** for selecting a specific year (multi-select supported).
  - **Region slicer** to focus analysis by region.
- Contains **navigation buttons** (via bookmarks) to jump to other detailed report pages.

### 2. Sales Dashboard
- Shows **sales performance trends** and geographic breakdown.
- Visuals include:
  - **Sales by Country** (Bar Chart)
  - **Sales by Region** (Stacked Bar)
  - **Monthly Sales Trend** (Line Chart grouped by Year & Month)
  - **Sales by Product Category & Subcategory** (Tree Map / Bar Chart)

### 3. Profit Analysis
- Focused on **profitability across regions and products**.
- Visual elements:
  - **Profit by Product** (Bar Chart)
  - **Profit by Country** (Map/Bar)
  - **Monthly Profit Trend** (Line Chart)
  - **Profit Margin Comparison** across categories

### 4. Customer Insights
- Helps understand **customer contribution and distribution**.
- Charts and visuals:
  - **Top 10 Customers by Sales**
  - **Top Customers by Profit**
  - **Customer Count by Region**
  - **Customer segmentation by category/subcategory**

### 5. Product Performance
- Evaluates the **best and worst performing products**.
- Includes:
  - **Sales by Product Name**
  - **Contribution by Subcategory**
  - Highlighting top and bottom product performers based on revenue and profit.

### 6. Region-Wise Performance
- Compares performance across **regions and countries**.
- Includes:
  - **Sales by Region and Country**
  - **Profit by Country**
  - **Sales and Profit Ranking by Region**
  - Drill-down capabilities for country → city

### 7. Order Analysis
- Analyzes order volume and order-related trends.
- Shows:
  - **Total Orders by Region and Category**
  - **Average Order Quantity**
  - **Monthly Order Volume**
  - **Top 10 Cities by Order Volume**

---

## 📌 Key Features

- ✅ **Interactive filters**: Region, Year, Category, Subcategory, Product
- ✅ **Dynamic tooltips** on charts and cards
- ✅ **Custom DAX Measures**:
  - Total Sales = SUM(SalesAmount)
  - Total Profit = SUM(Profit)
  - Total Orders = COUNT(OrderNumber)
  - Monthly Trend measures using `DATEADD` and `TOTALYTD`
- ✅ **Clean visual hierarchy** and formatting
- ✅ **Page navigation using bookmarks and buttons**

---

## 🧰 Tools & Technologies Used

| Tool       | Purpose                       |
|------------|-------------------------------|
| Power BI   | Data Modeling & Visualization |
| DAX        | Calculated measures & KPIs    |
| AdventureWorks Dataset | Sales data simulation |

---

## 📈 KPIs Tracked

- **Total Sales**
- **Total Profit**
- **Profit Margin**
- **Order Volume**
- **Sales Trend (Monthly & Yearly)**
- **Top Products / Customers**
- **Sales & Profit by Region**

---

## 📂 Data Sources

- The dataset used is **AdventureWorks**, commonly used for business analytics practice. It includes:
  - Customer Info
  - Product Categories & Subcategories
  - Order & Sales Data
  - Country/Region mappings
  - Time dimension
