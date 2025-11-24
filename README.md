# 🛒 Customer Behavior Analysis – Detailed Data Analytics Project

This repository contains a complete end-to-end **Customer Behavior Data Analytics Project** using **Python**, **SQL Server**, and **Power BI**.  
The project aims to uncover customer purchasing patterns, revenue trends, demographic insights, product performance, and behavioral segmentation.

---

# 📷 Power BI Dashboard Screenshot

Below is the main dashboard preview created using Power BI:

![customer_behavior_dashboard (1)_page-0001](https://github.com/user-attachments/assets/403f8935-7e4a-425b-ac45-0846a90156a3)


---

# 📌 Project Summary

This project performs full-cycle data analysis, starting from data cleaning and transformation in Python, followed by generating structured insights using SQL Server, and finally developing an interactive Power BI dashboard to visually communicate findings.

The goal of the project is to understand:

- What age groups purchase the most?
- Which categories generate the highest revenue?
- Which products perform best?
- How subscription status influences spending?
- Which shipping methods customers prefer?
- Patterns in customer satisfaction through review ratings

---

# 📁 Project Structure

├── Customer_Shopping_Behavior_Analysis.ipynb # Python cleaning + EDA

├── updated_data.csv # Cleaned dataset

├── customer_behavior_sql_queries.sql # SQL insights file

├── customer_behavior_dashboard.pdf # Power BI dashboard

├── customer_behavior_dashboard.jpg # Dashboard screenshot

└── README.md # Project documentation

---

# 🧹 1. Data Preparation & Cleaning (Python)

The dataset was cleaned and transformed using **Pandas**, ensuring accuracy and consistency across analyses.  
Key preprocessing steps include:

- Removing missing values  
- Standardizing data types  
- Creating Age Groups for segmentation  
- Fixing text and formatting issues  
- Conducting univariate & bivariate EDA  
- Generating summary statistics  
- Exporting final cleaned dataset  

Python visualizations provided insights into:

- Review rating distribution  
- Category-based revenue  
- Age group spending levels  
- Subscription behavior  

The transformed dataset (`updated_data.csv`) was then used for SQL queries and dashboard development.

---

# 🧪 2. SQL Server Analysis (Insight Extraction)

SQL Server was used to extract deep insights from the cleaned dataset.  
Key business questions answered:

### 🔹 Top 3 products inside each category  
Using:
ROW_NUMBER() OVER (PARTITION BY category ORDER BY COUNT(*) DESC)

### 🔹 Category-level performance  
Revenue & sales summaries.

### 🔹 Shipping preference patterns  
Finding the most preferred delivery types.

### 🔹 Subscription vs Non-Subscription performance  
Who spends more?

### 🔹 Review rating patterns  
Identifying well-rated product categories.

SQL provides structured, accurate insights that were later visualized in Power BI.

---

# 📊 3. Power BI Dashboard (Interactive Insights)

The Power BI dashboard allows dynamic filtering and visual exploration.

### ⚡ Dashboard includes:
- KPI Cards  
  - Total Customers  
  - Avg Purchase Amount  
  - Avg Review Rating  
- Revenue by Category  
- Sales by Category  
- Revenue by Age Group  
- Sales by Age Group  
- Subscription Status Donut  
- Gender Filter  
- Category Slicer  
- Age Group Slicer  
- Shipping Type Filter  

The dashboard makes analysis visually intuitive and business-friendly.

---

# 🔍 4. Key Insights

### ⭐ Category & Revenue
- **Accessories** generate the highest revenue.
- **Clothing** dominates sales volume.

### ⭐ Age Group Behavior
- **Young Adults (18–35)** purchase the most.
- Adults contribute strong revenue as well.

### ⭐ Subscription Analysis
- Only **27%** are subscribers.
- Subscribers spend **more per transaction**.

### ⭐ Shipping Trends
- **Standard** & **Express** shipping are most common.

### ⭐ Customer Satisfaction
- Average rating is **3.75**, indicating moderate satisfaction.

---

# 📘 Technologies Used

| Tool | Purpose |
|------|---------|
| **Python** | Data cleaning & EDA |
| **SQL Server** | Insights via queries |
| **Power BI** | Dashboard development |
| **Jupyter Notebook** | Python analysis |
| **CSV Dataset** | Data source |

---

# 📦 Dataset Columns

| Column | Description |
|--------|-------------|
| customer_id | Unique identifier |
| age | Customer age |
| gender | Gender |
| age_group | Segmented age buckets |
| category | Product category |
| item_purchased | Specific item |
| purchase_amount | Purchase value |
| review_rating | Customer rating |
| subscription_status | Yes/No |
| shipping_type | Delivery method |
| previous_purchases | Past purchase count |

---

# 🏁 Conclusion

This project demonstrates a complete data analytics pipeline:

- Data Cleaning  
- SQL Insight Extraction  
- Dashboard Storytelling  

It shows how combining Python, SQL Server, and Power BI can produce valuable, actionable business insights.

---

