# Customer Behavior Dashboard 📊

An interactive Power BI dashboard designed to analyze and visualize retail customer behavior, sales performance, and demographics. This project provides actionable insights into purchasing patterns, revenue drivers, and subscription metrics to help businesses optimize marketing strategies and boost sales.

---

## 🚀 Project Overview

This dashboard serves as a comprehensive tool for stakeholders to track Key Performance Indicators (KPIs) across different customer segments. By filtering data dynamically by subscription status, gender, product category, and shipping preferences, users can uncover granular trends in shopping behaviors.

### Key Insights Delivered:
* **Customer Segmentation:** Analysis of sales distribution across distinct age groups (Adult, Senior, Middle-aged, Young Adult).
* **Revenue Optimization:** Identification of high-performing product categories and their financial impact.
* **Subscription Value:** Evaluation of the purchasing power and review behaviors of subscribed vs. non-subscribed customers.

---

## 📈 Key Features & KPIs Tracked

The dashboard is structured around three main analytical pillars:

### 1. Executive Summary Cards (KPIs)
* **Number of Customers:** Total unique customer count based on applied filters.
* **Average Purchase Amount ($):** The mean value spent per transaction.
* **Average Review Rating:** Customer satisfaction tracking on a 5-star scale.

### 2. Demographic & Subscription Analysis
* **% of Customers by Subscription Status:** A donut chart displaying the proportion of subscribed users.
* **Revenue & Sales by Age Group:** Horizontal bar charts comparing consumer behavior across age brackets to target age-specific marketing campaigns.

### 3. Product Performance
* **Revenue by Category:** Bar chart detailing the gross revenue generated per product category.
* **Sales by Category:** Bar chart tracking the volume of items sold per category.

### 4. Interactive Slicers (Left Panel)
* **Subscription Status** (Yes/No)
* **Gender** (Male/Female)
* **Category** (e.g., Accessories, Clothing, etc.)
* **Shipping Type**

---

## 🛠️ Tech Stack & Tools Used

* **Data Visualization:** Power BI Desktop
* **Data Transformation:** Power Query (ETL process)
* **Modeling Language:** DAX (Data Analysis Expressions) for calculated measures and KPIs.
* **Design & Theme:** Customized dark blue and purple modern minimalist theme for high readability.

---

## 🖼️ Dashboard Preview

![Dashboard Screenshot](snapshot%20of%20dashboard.png.)

---

## 🧠 DAX Measures Used (Examples)

Here are some of the core metrics calculated for this dashboard:

```dax
// Example: Total Number of Customers
Total_Customers = DISTINCTCOUNT(CustomerData[CustomerID])

// Example: Average Purchase Amount
Avg_Purchase_Amount = AVERAGE(CustomerData[PurchaseAmount])
