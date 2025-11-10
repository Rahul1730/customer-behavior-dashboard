# 🧠 Customer Behavior Dashboard

![Dashboard Preview]("[C:\course\Project portfolio\Snap shot customer Behavior dashboard.png](https://github.com/Rahul1730/customer-behavior-dashboard/blob/main/Snap%20shot%20customer%20Behavior%20dashboard%20(2).png")

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python">
  <img src="https://img.shields.io/badge/MySQL-Database-orange.svg" alt="MySQL">
  <img src="https://img.shields.io/badge/Power%20BI-Visualization-yellow.svg" alt="Power BI">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License">
</p>

---

## 📋 Overview

The **Customer Behavior Dashboard** is a data analytics and visualization project designed to understand customer purchasing trends, revenue distribution, and demographic behavior.  
This project integrates **Python**, **MySQL**, and **Power BI** to create a full data workflow — from data extraction to visualization.

It provides business insights such as:
- Customer segmentation and subscription behavior  
- Revenue contribution by product category  
- Purchase frequency and preferred shipping methods  
- Average spending and review trends  

---

## 🧩 Tech Stack

| Tool | Purpose |
|------|----------|
| 🐍 **Python** | Data extraction, cleaning, and transformation |
| 🗄️ **MySQL** | Data storage and querying |
| 📊 **Power BI** | Visualization and interactive dashboard |

---

## ⚙️ Project Workflow

### 1️⃣ **Data Extraction**
- Retrieved raw customer and transaction data from **MySQL** database.

### 2️⃣ **Data Cleaning & Transformation (Python)**
Used libraries such as:
```python
import pandas as pd
import numpy as np
import sqlalchemy

Performed:

Null value handling

Data normalization

Revenue and frequency aggregation

Age group and category segmentation

3️⃣ Database Layer (MySQL)

Example table structure:

customers — customer demographics and subscription info

orders — order details and purchase amount

reviews — customer review ratings

4️⃣ Visualization (Power BI)

Connected MySQL or cleaned CSV output directly to Power BI

Designed interactive visuals for KPIs, trends, and filters

📊 Dashboard Metrics
KPI	Description
675	Total Customers
3.72	Average Review Rating
₹60.41	Average Purchase Amount
₹41K	Total Revenue
📈 Key Visuals

Donut Chart — % of customers by subscription

Bar Chart — Revenue by Category & Customer Count by Category

Horizontal Bars — Revenue by Age Group & Frequency of Sales

🎛️ Filters Used

Subscription Status → Yes / No

Gender → Male, Female

Category → Accessories, Clothing, Footwear, Outerwear

Shipping Type → Free Shipping, Express, 2-Day, Standard, etc.
