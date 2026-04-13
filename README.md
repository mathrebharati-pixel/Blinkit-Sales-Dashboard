# 🛒 Blinkit Sales & Outlet Performance Dashboard

## 📌 Project Overview

This project analyzes Blinkit's sales data to understand product performance, outlet efficiency, and customer behavior using Power BI.

The dashboard provides insights into sales trends, outlet performance, item visibility, and customer satisfaction.

---

## 🎯 Objectives

* Analyze overall sales performance
* Identify top-performing products and outlets
* Understand the impact of item visibility on sales
* Evaluate customer satisfaction using ratings
* Compare performance across Tier 1, Tier 2, and Tier 3 cities

---

## 📊 Dataset Information

### 🧾 Item Details

* Item Identifier
* Item Type
* Item Fat Content
* Item Weight
* Item Visibility

### 💰 Sales Details

* Sales
* Rating
* Outlet Identifier

### 🏪 Outlet Details

* Outlet Establishment Year
* Outlet Location Type (Tier 1/2/3)
* Outlet Size
* Outlet Type

---

## 🧹 Data Cleaning & Transformation

* Handled missing values (Item Weight, Visibility)
* Standardized categorical values (Fat Content)
* Removed duplicates
* Created new columns:

  * Sales per Kg
  * Years of Operation

---

## 🧩 Data Modeling

* Fact Table: Sales Data

* Dimension Tables:

  * Items
  * Outlets
  * Outlet Location

* Established relationships using a star schema model

---

## 📐 DAX Measures

* Total Sales
* Average Sales per Outlet
* Average Rating (CSAT)
* Sales per Kg

---

## 📊 Dashboard Features

* KPI Cards (Total Sales, Avg Sales, Rating)
* Sales by Item Type
* Outlet Performance Analysis
* Fat Content Distribution
* Sales Trend Analysis
* Item Visibility vs Sales (Scatter Plot)

---

## 🎛 Interactivity

* Slicers for:

  * Outlet Location (Tier)
  * Outlet Size
  * Outlet Type
  * Item Fat Content

---

## 📈 Key Insights

* Tier 1 outlets generate the highest sales
* Some products have high visibility but low sales
* Large outlets perform better than small ones
* Customer ratings vary across outlet types

---

## 🛠 Tools Used

* Power BI
* Power Query
* DAX

---

## 📷 Dashboard Preview
# Sales Dashboard
<img width="1298" height="733" alt="Screenshot 2026-04-13 173511" src="https://github.com/user-attachments/assets/fbf8a01a-c218-47b6-8579-51290627b18a" />

# Outlet Dashboard
<img width="1312" height="715" alt="image" src="https://github.com/user-attachments/assets/483d8184-ab48-4dd0-a3fe-51b6311fe930" />



---

## 🚀 Conclusion

This dashboard helps in making data-driven decisions to improve sales performance, optimize outlet operations, and enhance customer satisfaction.
