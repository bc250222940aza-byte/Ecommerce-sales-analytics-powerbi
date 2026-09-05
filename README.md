# Interactive E-Commerce Sales & Profitability Dashboard (Power BI)

## 📌 Project Overview
An interactive Power BI dashboard designed to analyze e-commerce operations, sales performance, and profitability across categories, sales channels, and payment methods.

## 📸 Dashboard Preview
![Dashboard Overview](Screenshots/dashboard_preview.png)

## 🔑 Key Business Metrics & DAX Measures
* **Total Net Sales:** `SUM(Orders[Net Sales (PKR)])`
* **Total Gross Profit:** `SUM(Orders[Gross Profit (PKR)])`
* **Profit Margin %:** `DIVIDE([Total Gross Profit], [Total Net Sales], 0)`

## 🛠️ Features
* Dynamic cross-filtering and date range sliders.
* Category breakdown and payment method analysis.
* Conditional formatting for negative profitability tracking.

## 📂 Repository Structure
* `Ecommerce_Dashboard.pbix` - Main Power BI report
* `Dataset/` - Raw data files (Orders, Products, DateTable)
* `Screenshots/` - Visual previews
