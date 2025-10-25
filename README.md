# 🛍️ Retail Orders Data Analysis (Python + SQL Server)

## 📘 Overview
This project focuses on analyzing retail order data using **Python** and **Microsoft SQL Server**.  
The goal is to clean and transform raw retail data, store it in a SQL database, and extract valuable business insights such as:
- Top-selling products
- Regional performance
- Monthly growth comparisons
- Category and sub-category profit analysis

---

## 🧰 Tools & Technologies
- **Python** → For data cleaning and preprocessing using Pandas  
- **SQLAlchemy** → For database connectivity between Python and SQL Server  
- **Microsoft SQL Server** → For data storage and SQL-based analytics  

---

## ⚙️ Project Workflow
1. **Data Cleaning in Python:**  
   The dataset is read from a CSV file, cleaned, and transformed. New columns like `discount`, `sale price`, and `profit` are calculated.

2. **Database Connection:**  
   The cleaned dataset is connected to SQL Server using SQLAlchemy and stored in a new database table.

3. **SQL Analysis:**  
   SQL queries are executed to extract insights such as top products by revenue, sales growth trends, and category performance.

---

## 🧾 Configuration
- **Default Server Name:** `PAVITRA\MSSQL`  
- **Default Database Name:** `TestDB`  
- **Default Table Name:** `orders_data`

> ⚠️ Before running, **replace** the server name and database name with your own:
> - Replace `PAVITRA\MSSQL` → with your SQL Server instance  
> - Replace `TestDB` → with your desired database name  

Example:  
`YOUR_SERVER_NAME\SQLSERVER`  
`YOUR_DATABASE_NAME`

---

## 📊 Insights Generated
- Top 10 revenue-generating products  
- Top 5 best-selling products per region  
- Month-over-month sales comparison (2022 vs 2023)  
- Category-wise month with highest sales  
- Sub-category with highest profit growth  

---

## 📈 Business Impact
This analysis helps businesses:
- Identify their most profitable products  
- Understand seasonal and regional trends  
- Make data-driven decisions for pricing and marketing  
- Improve overall sales strategy and forecasting  

---

## 🧠 Future Enhancements
- Add visualization dashboards (Power BI or Tableau)  
- Automate ETL pipelines using Python  
- Deploy reports as a web dashboard using Flask or Streamlit  

---

## 📄 License (MIT)
