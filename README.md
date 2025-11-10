# 🛍 Customer Behaviour Analysis — SQL + Power BI + Python

![SQL](https://img.shields.io/badge/SQL-Data%20Analysis-blue?logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-Data%20Processing-yellow?logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard%20Visualization-F2C811?logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project analyzes **customer purchasing behavior** to understand:

- Which products perform best
- What drives revenue
- How subscribers differ from non-subscribers
- Which customer segments (age group, category, gender) contribute most

The workflow includes:

- ✅ Data cleaning, exploration, and exporting results using **Python (Jupyter Notebook)**
- ✅ Business insights extraction using **SQL**
- ✅ Dashboard storytelling using **Power BI**

---

## 🔧 Tools & Technologies Used

| Category | Tech Used |
|----------|-----------|
| Data Processing & HTML Export | Python (Pandas, Jupyter Notebook) |
| Data Analysis | SQL (PostgreSQL / MySQL) |
| Visualization | Power BI |
| File Formats | `.pbix`, `.sql`, `.html` |

---

## 🧠 What This Project Does

✔ Extracts insights using SQL  
✔ Segments customers (New / Returning / Loyal)  
✔ Identifies best performing products  
✔ Compares subscriber vs non-subscriber revenue  
✔ Shows revenue breakdown by gender, age group, shipping type, discount usage, etc.  

---

## 📊 Key Business Questions (SQL Analysis)

| Question | Description |
|----------|-------------|
| Which gender generates more revenue? | Groups by gender and sums purchase amount. |
| Do discounts improve revenue contribution? | Filters discounted purchases above average purchase amount. |
| What products have the highest ratings? | Ranks based on average review rating. |
| Are subscribers more profitable? | Compares avg spend + total revenue by subscription. |
| Best-selling products by category? | Uses `ROW_NUMBER()` window function. |
| Do repeat buyers also subscribe? | Checks subscription behavior for loyal buyers. |
| Revenue contribution by age group? | Revenue aggregated by age segment. |

📄 SQL File: **`customer_behaviour.sql`**

---

## 🐍 Python Component (HTML output)

Python was used to:

- Load and explore dataset using Pandas
- Generate summary statistics
- Export findings into an **HTML report**

📄 HTML Output: **`customer_behaviour.html`**

---

## 📈 Power BI Dashboard

The Power BI file visualizes SQL & Python insights.

📊 Dashboard File: **`customer behavior dashboard.pbix`**

---

### 🖼 Dashboard Screenshot

> Save your screenshot in a folder named `screenshots` and name it `dashboard.png`

