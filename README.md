# 📊 Electronics Sales Analysis & Market Basket Analysis

📌 Project Overview

This project focuses on analyzing electronics sales transactions to extract business insights about top products, customer behavior, and sales trends.
The analysis includes:

Data cleaning and preparation

Exploratory Data Analysis (EDA)

Visualization of sales by products, cities, months, days, and hours

Market Basket Analysis (MBA) to find frequently purchased product combinations

Building Association Rules using Apriori Algorithm

---
📂 Dataset Description

The dataset is a CSV file containing sales records for electronics products with the following columns:

Order ID: Unique identifier for each order

Product: Name of the product

Quantity Ordered: Number of items ordered

Price Each: Price per item

Order Date: Date and time of order

Purchase Address: Customer address

Month / Day / Year / Hour: Extracted from Order Date for analysis

Sales: Total sales per order

City: Extracted from Purchase Address

---

⚙️ Methodology

The project followed these main steps:

Data Cleaning & Transformation: Handling missing values, duplicates, and splitting date/time into separate columns.

Exploratory Analysis: Visualizing top-selling products, sales by city, monthly and daily sales trends.

Advanced Analysis: Market Basket Analysis to find frequently purchased product combinations.

Visualizations: Bar charts, line charts and heatmaps

---

🔍 Exploratory Analysis Highlights

Top-selling products by number of orders, quantity, and sales revenue.

Cities contributing the most to total sales.

Sales trends by month, day, and hour.

Heatmaps showing peak sales hours and days.

---

📊 Market Basket Analysis (MBA)

Identifying products that are frequently bought together.

Generating association rules with support, confidence, and lift metrics.


---

💡 Key Insights

Certain products dominate sales across categories.

Sales are concentrated in specific cities and during certain hours of the day.

Customers tend to buy certain products together, which can help in recommendation strategies.

Monthly and daily sales trends reveal peak periods for marketing focus.

--- 

🛠️ Tools Used

Python (Pandas, Numpy) → Data cleaning and manipulation

Matplotlib & Seaborn → Data visualization

Mlxtend → Market Basket Analysis (Apriori and Association Rules)

---

📁 Project Files

* **[electronics-data.csv](path/to/your/Sales%20Data.csv)** → Raw dataset containing all orders and product details
* **[electronics-analysis.ipynb](path/to/your/EDA_Visualizations.ipynb)** → Jupyter Notebook with all analysis, plots, and Market Basket Analysis



