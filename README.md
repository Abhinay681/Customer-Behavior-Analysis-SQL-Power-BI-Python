🛍 Customer Behaviour Analysis — SQL + Power BI + Python
________________________________________
📌 Project Overview
This project analyzes customer purchasing behavior to understand:
•	What drives sales
•	Which products perform best
•	How customer segments contribute to revenue
•	How subscription status impacts spending
The workflow includes:
•	✅ Data cleaning, exploration, and exporting results using Python (Jupyter Notebook)
•	✅ Business insights extraction using SQL
•	✅ Dashboard storytelling using Power BI
________________________________________
🔧 Tools & Technologies Used
Category	Tech Used
Data Processing & HTML Export	Python (Pandas, Jupyter Notebook)
Data Analysis	SQL (PostgreSQL / MySQL)
Visualization	Power BI
File Formats	.pbix, .sql, .html
________________________________________
🧠 What This Project Does
✔ Extracts insights using SQL
✔ Segments customers (New / Returning / Loyal)
✔ Identifies best performing product categories
✔ Compares subscriber vs non-subscriber spending
✔ Shows revenue contribution by gender, age group, shipping type & discounts applied
✔ Uses Python to generate an HTML output report
________________________________________
📊 Key Business Questions (SQL Analysis)
Question	Description
Which gender generates more revenue?	Groups customers by gender and sums purchase amount.
Do discounts improve revenue contribution?	Filters discounted purchases above the average purchase amount.
What products have the highest ratings?	Ranks products based on average customer review rating.
Are subscribers more profitable?	Compares avg spend & total revenue of subscribers vs non-subscribers.
Best-selling products by category?	Uses ROW_NUMBER() window function.
Do repeat buyers also subscribe?	Checks subscription behavior for loyal buyers.
Revenue contribution by age group?	Aggregates revenue based on age group segment.
📄 SQL File: customer_behaviour.sql
________________________________________
🐍 Python Component (HTML Output)
The project contains a Jupyter Notebook, where:
•	Data is loaded using Pandas
•	Exploratory data analysis performed
•	The notebook is exported as an HTML report
📄 HTML Output: customer_behaviour.html (Generated using Python)
________________________________________
📈 Dashboard Highlights (Power BI)
The Power BI report visualizes the SQL + Python insights:
✅ Revenue by category
✅ Spending behavior — Subscribers vs Non-Subscribers
✅ Customer segmentation (New / Returning / Loyal)
✅ Sales & revenue breakdown by age group
✅ Impact of shipping type & discount usage
📊 Power BI Dashboard File: customer behavior dashboard.pbix

