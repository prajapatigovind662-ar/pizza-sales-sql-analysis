# 🍕 Pizza Sales Analysis (SQL Project)

## 📌 Project Overview
This project analyzes pizza sales data using SQL to uncover meaningful business insights. The analysis focuses on understanding revenue performance, identifying top-selling pizzas, analyzing category-wise contributions, and tracking sales trends over time. The goal is to demonstrate how SQL can transform raw transactional data into actionable insights for data-driven decision-making.

---

## 🎯 Objectives
- Calculate total revenue generated from pizza sales  
- Identify top-performing pizzas based on revenue  
- Analyze category-wise revenue contribution  
- Determine the top 3 pizzas within each category  
- Analyze cumulative revenue trends over time  

---

## 🗂 Dataset Description
The dataset consists of four related tables:

### Orders
Contains information about each order.
- order_id
- order_date
- order_time

### Order_Details
Contains the details of pizzas included in each order.
- order_details_id
- order_id
- pizza_id
- quantity

### Pizzas
Contains pizza size and pricing information.
- pizza_id
- pizza_type_id
- size
- price

### Pizza_Types
Contains pizza name, category, and ingredients.
- pizza_type_id
- name
- category
- ingredients

---

## 🛠 Tools Used
- SQL (MySQL / PostgreSQL)
- GitHub
- PowerPoint / Canva for presentation

---

## 📊 Key Analysis Performed
The following analysis was performed using SQL:

- Total revenue calculation using quantity and price
- Category-wise revenue contribution
- Identification of top 3 pizzas in each category using `RANK()`
- Cumulative revenue analysis using `SUM() OVER`

---

## 📈 Key Insights
- Certain pizza categories contribute significantly to overall revenue.
- A small number of pizzas generate a large share of total sales.
- Top 3 pizzas in each category act as major revenue drivers.
- Revenue trends show consistent growth over time.

---

## 🚀 Future Scope
- Build interactive dashboards using Power BI or Tableau
- Perform deeper analysis of customer ordering behavior
- Analyze seasonal sales patterns for better forecasting

---

## 💡 Skills Demonstrated
- SQL Joins
- Aggregations (SUM, GROUP BY)
- Subqueries
- Window Functions (RANK, SUM OVER)
- Data Analysis & Business Insights

---

## 📂 Project Structure
