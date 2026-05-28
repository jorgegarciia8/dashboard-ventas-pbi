# 📊 Olist E-Commerce Analytics Dashboard (Power BI)

> 🚀 **[Accede aquí a la Demo Interactiva en Power BI Service](https://app.powerbi.com/links/4z_roo3CcB?ctid=899789dc-202f-44b4-8472-a6d40f9eb440&pbi_source=linkShare)**

## 📌 Overview

This project presents an interactive Power BI dashboard built using the Brazilian E-Commerce Public Dataset (Olist).  
The goal is to analyze sales performance, customer behavior, logistics efficiency, and overall business profitability.

The solution transforms raw transactional data into actionable business insights through data modeling, Power Query transformations, and DAX measures.

---

## 🎯 Objective

The main objective of this project is to develop a Business Intelligence solution that enables decision-makers to:

- Monitor key performance indicators (KPIs)
- Analyze sales and revenue trends
- Understand customer behavior
- Evaluate logistics performance
- Identify business opportunities and risks

---

## 📂 Dataset

- Source: Kaggle - Olist E-commerce Dataset  
- Period: September 2016 – October 2018 (24 months)  
- Size: ~100,000 orders and 9 relational tables  

### Main Tables:
- Orders
- Order Items
- Payments
- Customers
- Products
- Reviews
- Geolocation
- Shipping
- Category Translation

---

## 🛠 Tools Used

- Power BI Desktop  
- Power Query (ETL process)  
- DAX (Data Analysis Expressions)  
- Star Schema Data Modeling  

---

## 🔄 Data Processing

The dataset was cleaned and transformed using Power Query:

- Standardized data types (dates, numeric, text)
- Handled missing values (imputation and null retention strategy)
- Removed duplicates from dimension tables
- Created calculated columns (delivery time, delays, volume)
- Built a dedicated date table for time intelligence

---

## 🧩 Data Model

A Star Schema model was implemented to optimize performance and analysis:

- Fact table: Orders / Order Items
- Dimension tables: Customers, Products, Payments, Reviews, Calendar

Relationships were established to ensure proper filtering and aggregation across all visualizations.

---

## 📊 Key KPIs

- 💰 Total Revenue: €537.21M  
- 📦 Total Orders: 99,000  
- ⭐ Average Rating: 4.09 / 5  
- 🚚 On-time Delivery Rate: 89.15%  
- 📈 Average Delivery Time: 12.09 days  
- 🛍 Unique Products: 32,000+  
- 👥 Total Customers: 99,000  

---

## 📈 Key Insights

- Revenue is highly concentrated in São Paulo and Rio de Janeiro (~50%)
- Customers show low retention (most users make only one purchase)
- Deliveries are consistently faster than promised (average -11 days)
- Strong seasonal patterns observed, especially in Q2
- Some product categories show significantly higher satisfaction than others

---

## 📊 Dashboard Structure

### 1. Executive Overview
- Global KPIs
- Revenue trends
- Geographic distribution
- ## 📸 Capturas del Dashboard

### Sales
![Sales Overview](images/1.png)

### 2. Customer Analysis
- Customer segmentation
- Purchase behavior
- Payment preferences
  
### Customers
![Customer Analysis](images/2.png)


### 3. Logistics Analysis
- Delivery performance
- Delay analysis
- Shipping efficiency

### Logistics Performance and Deliveries
![Logistics Efficiency](images/3.png)

---

## 📸 Dashboard Preview

![Overview](images/overview.png)
![Customer Analysis](images/customers.png)

---

## 📄 Full Technical Report

A complete technical documentation (In Spanish) of this project is available here:

👉 [Download Report](technical_report.pdf)

---

## 📸 Dashboard Preview

![Overview](images/overview.png)


## 🚀 Business Recommendations

- Improve customer retention strategies
- Optimize delivery promise times
- Expand market share in underperforming regions
- Investigate low-performing product categories
- Enhance logistics planning in high-delay areas

---

## 📌 Conclusion

This project demonstrates end-to-end data analysis capabilities, from raw data processing to actionable business insights.  
It showcases skills in data modeling, KPI development, and interactive dashboard design using Power BI.


## LINKEDIN

www.linkedin.com/in/jorge-garcia-martinez-bb6b8b282
