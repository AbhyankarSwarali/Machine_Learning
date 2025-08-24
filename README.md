# E-commerce Data Analysis

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
🔹 Basic Queries

List all unique cities where customers are located.

Count the number of orders placed in 2017.

Find total sales per product category.

Calculate % of orders paid in more than 1 installment.

Count customers from each state (visualized using bar chart).

🔹 Intermediate Queries

Number of orders per month in 2018 (bar chart).

Average number of products per order grouped by city.

% of total revenue contributed by each product category.

Correlation between product price and purchase frequency (scatter plot).

Total revenue by seller, ranked (bar chart).

🔹 Advanced Queries

Moving average of order values per customer.

Cumulative monthly sales by year.

Year-over-year sales growth.

Customer retention rate (within 6 months of first purchase).

Top 3 customers by spending per year (visualized).

📈 Visualizations

Bar plots of customer distribution, monthly orders, top sellers, and top customers.

Scatter plot showing relationship between product price and number of orders.

Annotated bar charts for better readability.

🔍 Insights from Visualizations

Customer Distribution: A few states contribute the majority of customers, indicating regional concentration of buyers.

Monthly Orders (2018): Certain months (e.g., holiday/festive seasons) have significantly higher order volumes, suggesting strong seasonality.

Top Sellers: Revenue is concentrated among a handful of sellers, highlighting seller performance inequality.

Product Price vs Orders: Negative correlation observed — lower-priced categories are ordered more frequently, while high-priced items sell less often.

Top Customers per Year: A small group of customers contributes disproportionately to annual revenue, showing the importance of high-value customers.

🚀 How to Run

Ensure your MySQL database (ecommerce) is running with the required tables (customers, orders, order_items, products, payments).

Update your database connection credentials in the notebook:

db = mysql.connector.connect(
    host='127.0.0.1',
    user='root',
    password='your_password',
    database='ecommerce'
)


Open the notebook:

jupyter notebook your_notebook.ipynb


Run all cells sequentially to view results.

📂 Outputs

Tabular outputs for SQL queries.

Visualizations for customer trends, sales growth, and category contributions.

Business KPIs such as retention rate, YoY growth, and revenue shares.

👩‍💻 Author

Your Name
