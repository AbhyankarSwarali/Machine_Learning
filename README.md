# Target E-commerce Data Analysis

## 📌 Overview

This project performs SQL-based analysis on an E-commerce database using Python, MySQL, and visualization libraries. It answers basic, intermediate, and advanced business questions such as customer distribution, sales trends, revenue contribution, customer retention, and year-over-year growth.

The notebook demonstrates how to connect a MySQL database with Python (mysql.connector) and retrieve insights using SQL queries, combined with pandas and seaborn/matplotlib for data manipulation and visualization.

## ⚙️ Requirements
- Python 3.x
- MySQL Database (with an ecommerce schema)
- Python libraries:
- numpy
- pandas
- matplotlib
- seaborn
- mysql.connector

## 📊 Analysis Covered
### 🔹 Basic Queries
1. List all unique cities where customers are located.
2. Count the number of orders placed in 2017.
3. Find total sales per product category.
4. Calculate % of orders paid in more than 1 installment.
5. Count customers from each state (visualized using bar chart).

### 🔹 Intermediate Queries
1. Number of orders per month in 2018 (bar chart).
2. Average number of products per order grouped by city.
3. % of total revenue contributed by each product category.
4. Correlation between product price and purchase frequency (scatter plot).
5. Total revenue by seller, ranked (bar chart).

### 🔹 Advanced Queries
1. Moving average of order values per customer.
2. Cumulative monthly sales by year.
3. Year-over-year sales growth.
4. Customer retention rate (within 6 months of first purchase).
5. Top 3 customers by spending per year (visualized).

## 📈 Visualizations
* Bar plots of customer distribution, monthly orders, top sellers, and top customers.
* Scatter plot showing relationship between product price and number of orders.
* Annotated bar charts for better readability.

## 🔍 Insights from Visualizations
- Customer Distribution: A few states contribute the majority of customers, indicating regional concentration of buyers.
- Monthly Orders (2018): Certain months (e.g., holiday/festive seasons) have significantly higher order volumes, suggesting strong seasonality.
- Top Sellers: Revenue is concentrated among a handful of sellers, highlighting seller performance inequality.
- Product Price vs Orders: Negative correlation observed — lower-priced categories are ordered more frequently, while high-priced items sell less often.
- Top Customers per Year: A small group of customers contributes disproportionately to annual revenue, showing the importance of high-value customers.

## 🚀 How to Run
1. Ensure your MySQL database (ecommerce) is running with the required tables (customers, orders, order_items, products, payments).
2. Update your database connection credentials in the notebook:
```
db = mysql.connector.connect(
    host='127.0.0.1',
    user='root',
    password='your_password',
    database='ecommerce')
```
3. Open the notebook:
```
jupyter notebook your_notebook.ipynb
```
4. Run all cells sequentially to view results.

## 📂 Outputs
- Tabular outputs for SQL queries.
- Visualizations for customer trends, sales growth, and category contributions.
- Business KPIs such as retention rate, YoY growth, and revenue shares.

## 👩‍💻 Author
**Abhyankar Swarali**

### Happy Learning !!
