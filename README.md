# Indiakart_Project
# 🛒 IndiaKart E-Commerce Analytics Dashboard

An interactive, multi-page **Power BI** dashboard that unifies e-commerce operations across **Customer, Inventory, Order Items, Logistics, Product, and Supplier** performance. It turns raw transactional data into actionable insights for regional targeting, inventory management, margin preservation, and supplier evaluation.

> Built as part of my Data Analyst internship.

## 📌 Table of Contents
- Project Overview
- Dashboard Pages & Key Insights
- Data Model
- Challenges & Solutions
- Tools & Skills Used
- Screenshots
- How to Use
- Author

## 🎯 Project Overview

IndiaKart's operational data lived in separate areas: customers, stock, orders, shipping, products, and vendors. This project connects all of them in one Power BI report so that business teams can:

- Identify high-performing regions and customer segments
- Monitor warehouse stock against re-order levels to prevent stockouts
- Understand profit margins, GST, and discount impact by category
- Evaluate suppliers and logistics partners

## 📊 Dashboard Pages & Key Insights

### 1. Customer Analytics
- Tracked active customers across **18 states and 50 cities**
- Uncovered regional dominance, with **Uttar Pradesh leading with 1,860 customers**
- Segmented users into **Regular, Premium, Budget, New, and Inactive** profiles

### 2. Inventory & Fulfillment Monitoring
- Visualized warehouse stock availability across regional locations (e.g., **Chennai-WH5 leading with 47,400 units**)
- Compared stock against re-order levels to prevent stockouts
- Real-time stock status: *In Stock*, *Low Stock*, *Out of Stock*

### 3. Profitability & Pricing Analysis
- Analyzed product revenue, profit margins, and discount impact across categories
- Tracked **average GST rate (12.30%)**
- Identified underperforming SKUs (e.g., *Top 10 Products with Least Revenue*)

### 4. Logistics & Supplier Evaluation
- Monitored order fulfillment channels, payment modes, and shipping partner distribution
- Analyzed vendor cost drivers and **payment terms (90–135 days)**

## 🗂️ Data Model

The report uses a scalable **Star Schema** connecting the operational tables (Customer, Inventory, Order Items, Logistics, Product, Supplier) around shared dimensions, designed to avoid circular dependencies.

---

## 🧩 Challenges & Solutions

| Challenge | Solution |
|-----------|----------|
| **Complex data relationships:** connecting customers, logistics, inventory, and suppliers | Designed a scalable **Star Schema** data model with no circular dependencies |
| **High-volume categories:** hundreds of product SKUs and subcategories were hard to visualize clearly | Used **dynamic filters, Top-N rankings**, and custom **DAX** metrics |
| **Stock-out & re-order tracking:** isolating stock status percentages | Wrote custom **DAX measures** to classify inventory as In Stock / Low Stock / Out of Stock in real time |

---

## 🛠️ Tools & Skills Used

- Power BI (Dashboard design, Data Modeling)
- DAX (custom measures)
- Power Query (data cleaning & transformation)
- Star Schema modeling
- KPI tracking, segmentation, inventory & supplier analytics

## 👩‍💻 Author

**Deepshika Sharma**
Data Analyst | Mumbai, India
🔗 LinkedIn: linkedin.com/in/deepshika-sharma-90b896399
📧 Email: deep.979sharma@gmail.com

⭐ If you found this project useful, consider giving the repo a star!
