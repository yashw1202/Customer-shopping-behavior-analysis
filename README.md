# 📊 Customer Behavior Analysis — Data Analytics Project

This project explores customer purchasing patterns using a **Customer Behavior Dataset**, with a full end-to-end workflow involving **data cleaning, SQL analysis, Python visualizations, and Power BI dashboards**. The goal is to uncover actionable insights about customer behavior, spending patterns, product performance, and subscription tendencies.

---

## 🚀 Project Overview

This analysis pipeline includes:

✔ **Data Cleaning** using *Pandas*  
✔ **MySQL Database Integration**  
✔ **SQL Queries** for analytical question solving  
✔ **Python Visualizations** using *Matplotlib & Seaborn*  
✔ **Business Insights & Observations** from each analysis  
✔ **Interactive Power BI Dashboard** featuring KPIs, charts, slicers, and filters

---

## 🛠️ Tech Stack

| Area | Tools |
|------|-------|
| Programming | Python (Pandas, NumPy) |
| Visualization | Matplotlib, Seaborn, Power BI |
| Database | MySQL |
| Data Handling | Pandas, CSV |
| Other | Jupyter Notebook |

---

## 📂 Project Workflow

### 1️⃣ Data Cleaning
- Handled missing & inconsistent values  
- Converted data types (numeric, categorical, boolean)  
- Standardized columns such as: `discount_applied`, `subscription_status`, `previous_purchases`, `age_group`  
- Added new features: customer segments (New, Returning, Loyal), repeat buyer flag, purchasing frequency grouping

### 2️⃣ SQL Integration (MySQL)
- Connected pandas DataFrame to MySQL using **pymysql**  
- Loaded cleaned data into SQL  
- Used SQL queries to answer analytical questions (aggregations, group-by, conditional logic)

### 3️⃣ Visualization (Matplotlib & Seaborn)
- Created bar charts, subplots, scatter plots, and distribution plots to visualize:
  - Revenue by gender, age group
  - Discount usage vs spend
  - Product ratings and top-sellers
  - Subscription patterns and repeat buyers

### 4️⃣ Power BI Dashboard
- Built an interactive dashboard containing:
  - Pie Charts, Column & Bar Charts, KPIs, Indicators
  - Slicers (Age Group, Category, Shipping Type, Subscription Status)
  - Filters for drill-down analysis

---

## 🧠 Business Questions & Insights

**Q1. Total revenue: Male vs Female**  
- Male customers contributed more revenue — dominance in certain categories/higher-value purchases.

**Q2. Discount users who still spent above average**  
- A cluster of high spenders exists even among discounted purchases — discounts attract some high-value customers.

**Q3. Top 5 products by average review rating**  
- These products show high satisfaction and can be promoted as hero products.

**Q4. Average purchase: Standard vs Express shipping**  
- Express/2-Day shipping customers spend more on average — potential premium segment.

**Q5. Subscribed vs Non-Subscribed spend**  
- Average spend is similar, but total revenue from non-subscribers is higher due to larger population size.

**Q6. Top 5 products with highest discount usage**  
- Hat, Sneakers, Coat, Sweater, Pants show highest discount usage.

**Q7. Customer segmentation (New / Returning / Loyal)**  
- Loyal customers form the largest segment — strong repeat purchase behavior.

**Q8. Top 3 most purchased products per category**  
- Clothing category dominates in purchase counts.

**Q9. Are repeat buyers (>5) likely to subscribe?**  
- Yes — repeat buyers are more likely to be subscribed.

**Q10. Total customer count per age group**  
- Young adults are the largest group.

**Q11. Revenue contribution by age group**  
- Young adults generate the most revenue.

---

