# 📊 Customer Shopping Behavior Analysis

**Author:** Zineb Rhallam  
**Role:** Junior Data Analyst  
**Tools:** Python, SQL (PostgreSQL), Power BI  

---

## 🚀 Project Overview
This project analyzes customer shopping behavior using **3,900 transactions** across multiple product categories. The main goal is to extract actionable insights into:

- Customer segmentation  
- Spending behavior  
- Product performance  
- Discount and promotion effectiveness  

These insights can guide **data-driven business decisions**, optimize marketing strategies, and improve customer retention.

---

## 📂 Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  
- **Key Features:**
  - **Customer Demographics:** Age, Gender, Location, Subscription Status  
  - **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
  - **Behavioral Data:** Discount Applied, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type  
- **Missing Values:** 37 missing values in `Review Rating` handled with category median imputation.

---

## 🛠 Data Preparation & Feature Engineering (Python)
- **Data Cleaning:** Standardized column names to `snake_case`.  
- **Feature Engineering:**  
  - `age_group` – categorize customers by age  
  - `purchase_frequency_days` – numerical representation of purchase frequency  
- **Data Consistency:** Dropped `promo_code_used` (redundant with `discount_applied`)  
- **Database Integration:** Loaded cleaned dataset into **PostgreSQL** for SQL analysis.

---

## 📝 SQL Analysis
Performed queries in PostgreSQL to uncover business insights:

1. **Revenue by Gender** – Compare male vs female revenue contribution  
2. **High-Value Customers Using Discounts** – Identify top spenders even with discounts  
3. **Top 5 Products by Review Rating** – Products with highest customer satisfaction  
4. **Average Purchase by Shipping Type** – Understand spending based on shipping method  
5. **Subscriber vs Non-Subscriber Spending** – Evaluate subscription program impact  
6. **Products with Highest Discount Usage** – Insights into promotion effectiveness  
7. **Customer Segmentation** – New, Returning, Loyal customers  
8. **Top 3 Products per Category** – Category-level bestsellers  
9. **Subscription Behavior of Repeat Buyers** – Link between loyalty and subscription adoption  
10. **Revenue Contribution by Age Group** – Identify most valuable demographics  

> SQL queries are included in [`customer_behavior.sql`](customer_behavior_sql_queries.sql)

---

## 📊 Visualization & Insights (Power BI)
- Built an **interactive dashboard** highlighting key trends:  
  - Revenue distribution  
  - Top products and categories  
  - Discount usage  
  - Customer segments and subscription behavior  
- Dashboard file: [`customer_behavior_dashboard.pbix`](customer_behavior_dashboard.pbix)  

---

## 🎯 Deliverables
1. **Python Scripts:** Data cleaning, transformation, feature engineering  
2. **SQL Queries:** Extract insights and simulate business transactions  
3. **Power BI Dashboard:** Visual storytelling for stakeholders  
4. **Project Report & Presentation:** Summary of findings and business recommendations  
5. **GitHub Repository:** Well-organized files for reproducibility  

---

## ⚡ How to Use
1. Clone the repository:  
```bash
git clone <your-repo-url>
