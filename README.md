# Business-Performance-Insights-Dashboard-using-SQL-Python-Power-BI

## 📘 Project Overview

Effective inventory and sales management are crucial for optimizing profitability in the retail and wholesale sectors. This project focuses on identifying inefficiencies and unlocking insights from transactional and inventory data to support data-driven decision-making.

### 🧩 Business Objectives

The goal of this analysis is to:

* 📉 Identify **underperforming brands** that may need promotional or pricing adjustments
* 🏆 Determine **top vendors** contributing significantly to sales and gross profit
* 📦 Analyze the **impact of bulk purchasing** on unit costs
* 🔄 Assess **inventory turnover** to reduce holding costs and improve operational efficiency
* 📊 Investigate **profitability differences** between high-performing and low-performing vendors

---

## 🔧 Project Workflow

This project was carried out in the following steps:

1. **Database Ingestion & SQL Analysis**

   * Loaded raw `.csv` files into a SQLite database
   * Performed complex SQL queries to clean, join, and create an **aggregated summary table** for further analysis

2. **Data Cleaning & EDA (Python)**

   * Used pandas and NumPy for data exploration, cleaning, and handling missing/inconsistent data
   * Conducted **Exploratory Data Analysis** to understand patterns and trends

3. **Business Questions & Insights**

   * Addressed key research questions aligned with business goals
   * Compared vendor performance, pricing strategies, and inventory dynamics

4. **Data Visualization (Python & Power BI)**

   * Created insightful charts using **Matplotlib** and **Seaborn**
   * Built a **Power BI dashboard** to visualize KPIs and highlight actionable insights

5. **Reporting**

   * Compiled a structured report summarizing findings, interpretations, and business recommendations

---





Due to GitHub size restrictions, the inventory.db file is not included. You can recreate the database by running ingestion_db.py after placing the CSVs in the /data folder.
