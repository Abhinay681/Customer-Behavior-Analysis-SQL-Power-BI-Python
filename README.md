# 🛍 Customer Behaviour Analysis — SQL + Power BI + Python

![SQL](https://img.shields.io/badge/SQL-Data%20Analysis-blue?logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-Data%20Processing-yellow?logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard%20Visualization-F2C811?logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project analyzes **customer purchasing behavior** to understand:

- What drives sales and revenue
- Which products and categories perform best
- Differences between subscribers vs non-subscribers
- Which customer segments contribute most to revenue

The workflow includes:

- ✅ Data cleaning, exploration, and HTML export using **Python (Jupyter Notebook)**
- ✅ Business insights extraction using **SQL**
- ✅ Dashboard storytelling using **Power BI**

---

## 🔧 Tools & Technologies Used

| Category | Tech Used |
|----------|-----------|
| Data Processing & HTML Export | Python (Pandas, Jupyter Notebook) |
| Data Analysis | SQL (PostgreSQL / MySQL) |
| Visualization | Power BI |
| Output Formats | `.pbix`, `.sql`, `.html` |

---

## 🧠 What This Project Does

✔ Extracts insights using SQL  
✔ Segments customers (New / Returning / Loyal)  
✔ Identifies best-performing product categories  
✔ Compares subscriber vs non-subscriber revenue  
✔ Shows revenue contribution based on gender, age group, shipping type, etc.

---

## 📊 Key Business Questions (SQL Analysis)

| Business Question | Insight Goal |
|------------------|--------------|
| Which gender generates more revenue? | Analyze spending trends by gender. |
| Do discounts improve revenue contribution? | Identify if discounts influence higher purchases. |
| What products have the highest review rating? | Understand customer satisfaction with products. |
| Are subscribers more profitable? | Compare avg purchase & total revenue. |
| Best-selling products by category? | Extract using `ROW_NUMBER()` window function. |
| Do repeat buyers also subscribe? | Analyze loyalty behavior. |
| Revenue contribution by age group? | Identify high-value age segments. |

📄 SQL File: **`customer_behaviour.sql`**

---

## 🐍 Python Component (HTML Output)

Python was used to:

- Load dataset using Pandas
- Generate insights and summaries
- Export the notebook results as HTML

📄 HTML File: **`customer_behaviour.html`**

---

## 📈 Power BI Dashboard

The Power BI dashboard visualizes all insights generated through SQL + Python.

📊 Dashboard File: **`customer behavior dashboard.pbix`**

---

### 🖼 Dashboard Screenshot


<img width="1162" height="641" alt="image" src="https://github.com/user-attachments/assets/b6c47222-c0cb-4140-8f07-7c9eed8cf652" />

---

## 🔹 KPIs (Top Cards)

| KPI | Meaning |
|-----|---------|
| **$59.76** | Average purchase amount |
| **3.75** | Average customer review rating |
| **3.9K** | Number of customers |

---

## 🔹 Dashboard Visuals

✨ Donut Chart – % of Customers (Subscribed vs Non-Subscribed)  
✨ Bar Chart – Revenue by Category  
✨ Bar Chart – Sales by Category  
✨ Horizontal Bar Chart – Revenue by Age Group  
✨ Horizontal Bar Chart – Sales by Age Group  

Filters available:

- Subscription Status
- Gender
- Category
- Shipping Type

---

## 💡 Insights & Findings

- **92.7% of customers are not subscribed** → huge conversion potential.
- **Clothing generates the highest revenue and sales volume.**
- **Young adults and middle-aged customers spend the most.**
- **Subscribers spend more per purchase**, proving subscription value.

---

## 🚀 Business Recommendations

| Insight | Recommendation |
|---------|--------------|
| Subscription adoption is low | Introduce free delivery or discount incentives |
| Clothing drives highest revenue | Increase promotions and SKU expansion |
| Young adults & middle-aged spend more | Target them with personalized campaigns |
| Higher spend per purchase | Introduce product bundles to increase cart value |

---

## 📁 Project Structure

