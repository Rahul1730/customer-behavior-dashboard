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
