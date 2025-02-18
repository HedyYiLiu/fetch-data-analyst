# Fetch - Data Analyst Take-Home Exercise 🚀

## Overview  
This repository contains my submission for the Fetch Data Analyst Take-Home Exercise. The project explores user transactions, identifies data quality issues, answers key business questions using SQL, and provides insights with a structured analysis.

---

## 📂 Contents  
- `exploratory_analysis.ipynb` – Python notebook for data exploration and visualization  
- `data_quality_findings.md` – Summary of data quality issues and challenges  
- `fetch_queries.sql` – SQL queries for closed-ended and open-ended questions  
- `stakeholder_summary.md` – Business insights and recommendations  
- `PRODUCTS_TAKEHOME.csv` – Product dataset  
- `TRANSACTION_TAKEHOME.csv` – Transaction dataset  
- `USER_TAKEHOME.csv` – User dataset  

---

## 🔍 Analysis & Key Findings  
### **1️⃣ Data Quality Issues**  
- **Missing Data** – Some records have null values for key fields like `birth_date` and `sale`.  
- **Duplicate Entries** – Some transaction records have identical timestamps and values.  

### **2️⃣ SQL Queries Answered**  
- **Top 5 brands by receipts scanned (users 21+)**  
- **Top 5 brands by sales (users with accounts for 6+ months)**  
- **Percentage of sales in Health & Wellness by generation**  
- **Identifying Fetch’s power users**  
- **Leading brand in Dips & Salsa category**  

### **3️⃣ Business Insights**  
- **Health & Wellness sales are disproportionately driven by Millennials (~45%)**  
- **Fetch's power users contribute over 60% of total sales and scan receipts at least 5 times a month**  
- **Brand X dominates the Dips & Salsa category with a 30% market share**  

---

## ▶️ How to Run the Analysis  
1. Clone the repository:  
   ```bash
   git clone https://github.com/YOUR_USERNAME/fetch-data-analyst-takehome.git
   cd fetch-data-analyst-takehome
