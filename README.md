# 🛒 Sales Retail Pipeline & Sales Analysis Project

> **Note:** This is my **first basic project** to understand and implement ETL, SQL and data visualization concepts using Python.

## 📌 Overview

This project presents an end-to-end **ETL (Extract–Transform–Load) pipeline** for a retail sales dataset followed by **exploratory data analysis (EDA)** and **visualizations** to derive meaningful business insights. The goal is to efficiently process raw sales data, clean and transform it into a usable format, and perform sales-based analysis to support data-driven decision-making for retail businesses.

---

## ⚙️ Technologies Used

| Category              | Tools/Libraries                      |
|----------------------|--------------------------------------|
| Programming Language | Python                                |
| Data Handling        | Pandas                                |
| Database             | SQL                                   |
| Visualization        | Matplotlib, Seaborn                   |

---

## 🔄 ETL Pipeline Stages

1. **Extract**
   - Imported sales data from `.csv` file containing details like Order_Date, Customer_ID, Product, Quantity, Price, and Region.

2. **Transform**
   - Cleaned missing values and duplicates  
   - Converted data types (e.g., dates, integers, floats)  
   - Created new features as needed (e.g., Sales = Quantity × Price)

3. **Load**
   - Loaded the cleaned and transformed dataset into a SQL database table for structured querying and further analysis

---

## 📊 Exploratory Data Analysis (EDA)

After the ETL process, detailed exploratory data analysis was carried out using Python to identify trends and generate actionable insights.

### Key Insights & Visualizations:
- **Top-performing Products** → Bar Chart  
- **Most Valuable Customers** → Bar Chart  
- **Sales Distribution Across Regions** → Pie Chart  
- **Monthly/Quarterly Sales Trends** → Line Plot

These visualizations help identify high-revenue segments, peak performance periods, and improvement areas to support management decisions.

---

## ✅ Project Outcomes

- Successfully built an ETL pipeline automating the extraction, transformation, and loading of retail data
- Generated **business-ready tables** inside SQL for querying
- Built **insightful charts** highlighting:
  - Top products generating maximum revenue
  - Loyal high-purchasing customers
  - Region-wise sales performance
- Provided recommendations to enhance sales and operational focus

---

## 📁 Folder Structure


