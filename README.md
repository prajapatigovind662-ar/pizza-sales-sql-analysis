# 🍕 Pizza Sales Analysis (SQL Project)

## 📌 Project Overview
This project analyzes pizza sales data using SQL to uncover meaningful business insights. The analysis focuses on revenue performance, identifying top-selling pizzas, analyzing category contributions, and understanding sales trends over time. The goal is to demonstrate how SQL can transform raw transactional data into actionable insights for data-driven decision-making.

---

## 🎯 Objectives
- Calculate total revenue generated from pizza sales  
- Identify top-performing pizzas based on revenue  
- Analyze category-wise revenue contribution  
- Determine the top 3 pizzas within each category  
- Analyze cumulative revenue trends over time  

---

## 🗂 Dataset Description

### Orders
Contains information about each order.

| Column | Description |
|------|-------------|
| order_id | Unique ID for each order |
| order_date | Date of the order |
| order_time | Time when the order was placed |

### Order_Details
Contains pizza order details.

| Column | Description |
|------|-------------|
| order_details_id | Unique order details ID |
| order_id | Reference to order |
| pizza_id | Reference to pizza |
| quantity | Number of pizzas ordered |

### Pizzas
Contains pizza pricing information.

| Column | Description |
|------|-------------|
| pizza_id | Unique pizza ID |
| pizza_type_id | Reference to pizza type |
| size | Pizza size |
| price | Price of the pizza |

### Pizza_Types
Contains pizza category and ingredients.

| Column | Description |
|------|-------------|
| pizza_type_id | Unique pizza type ID |
| name | Pizza name |
| category | Pizza category |
| ingredients | Ingredients used |

---

## 🛠 Tools Used
- SQL (MySQL / PostgreSQL)  
- GitHub  
- PowerPoint / Canva  

---

## 📊 Key Analysis
The following SQL analysis was performed:

- Revenue calculation using quantity and price  
- Category-wise revenue contribution  
- Top 3 pizzas per category using `RANK()` window function  
- Cumulative revenue analysis using `SUM() OVER` window function  

---

## 📈 Key Insights
- Certain pizza categories generate the highest revenue.  
- A small number of pizzas contribute significantly to total sales.  
- The top 3 pizzas in each category act as major revenue drivers.  
- Sales trends show consistent revenue growth over time.  

---

## 🚀 Future Scope
- Build interactive dashboards using **Power BI or Tableau**  
- Analyze customer ordering patterns  
- Study seasonal sales trends for better forecasting  

---

## 💡 Skills Demonstrated
- SQL Joins  
- Aggregate Functions  
- Window Functions  
- Data Analysis  
- Business Insight Generation  

---

## 📂 Project Structure

```
Pizza-Sales-Analysis-SQL
│
├── dataset
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   └── pizza_types.csv
│
├── sql_queries
│   └── pizza_sales_analysis.sql
│
├── presentation
│   └── pizza_sales_analysis.pptx
│
└── README.md
```

---

## 📌 Conclusion
This project demonstrates how SQL can be used to analyze transactional sales data and generate meaningful business insights. The analysis highlights revenue drivers, product performance, and sales trends that support better business decisions.

⭐ If you found this project helpful, feel free to star the repository.
