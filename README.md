

# 📊 Electronic Sales Performance Dashboard (Power BI)

A Power BI project analyzing electronic sales data to uncover **revenue drivers, profitability gaps, and regional performance differences** using time-intelligence metrics and interactive visuals.

---
<img width="972" height="547" alt="screenshot-1768769001980" src="https://github.com/user-attachments/assets/244a990d-cecb-45fe-8142-4fcd8fcbc7fb" />

## 🔍 Problem Statement

Sales performance was fragmented across channels, products, and regions with no unified view of:

* How sales evolve over time
* Which channels and categories actually drive profit
* Where geographic performance leaks occur

This project consolidates transaction data into a **decision-ready dashboard**.

---

## 📁 Dataset Overview

Transaction-level sales data containing:

* Order Date
* Sales, Unit Cost, Quantity
* Channel (Store, Online, Reseller, Catalog)
* Product Category & Subcategory
* Zone / State

Each row represents a single sales transaction.

---

## 🛠️ Data Preparation & Modeling

* Cleaned and standardized data types
* Created calculated fields: **Total Cost, Profit, Profit Margin**
* Built a dynamic **Date Table** using DAX
* Implemented a **star schema** for accurate time intelligence
* Enabled proper sorting and date relationships

---

## 📐 Key Measures (DAX)

* Total Sales
* Sales YTD
* Sales QTD
* Sales Last Month
* Sales Same Period Last Year
* YoY Variance & YoY Variance %
* Total Profit
* Profit Margin %

All monetary measures are formatted as currency.

---

## 📊 Dashboard Highlights

**KPIs**

* Total Sales: ₦56M
* Sales YTD: ₦16M
* Sales QTD: ₦3.23M
* Total Profit: ₦32.45M
* Profit Margin: 57.68%

**Visual Analysis**

* Sales trend over time
* Sales by channel
* Profit by zone
* Top product categories by sales

Interactive slicers:

* Year
* Zone
* State

---

## 🔥 Key Insights

* Physical stores drive the majority of revenue, creating channel dependency
* Online sales underperform relative to potential
* Sales are concentrated in Computers and Cameras
* Southern zones are significantly more profitable than Northern zones
* Strong overall margins mask regional and channel inefficiencies

---

## 🎯 Recommendations

* Scale online sales to reduce reliance on physical stores
* Focus inventory and promotions on high-performing categories
* Investigate logistics and pricing inefficiencies in underperforming zones
* Plan inventory and marketing around Q3–Q4 demand peaks

---

## ⚠️ Limitations

* No customer demographic data
* No marketing spend or promotion cost data
* External economic factors not included

---

## 📌 Tools Used

* Microsoft Power BI
* DAX
* Power Query

---

## 👤 Author

**Emmanuel Anowai**
Data Analyst

---
