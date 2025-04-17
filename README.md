# Task 7 - Basic Sales Summary from SQLite DB

## Objective:
Use SQL within Python to extract basic sales info and visualize it.

## Tools Used:
- Python (sqlite3, pandas, matplotlib)
- SQLite (no setup needed)
- Jupyter Notebook

## Steps:
1. Created a SQLite database and inserted sample sales data.
2. Queried the database using SQL to get total quantity and revenue per product.
3. Used Pandas to load and display the data.
4. Visualized revenue by product using a bar chart (Matplotlib).

## Output:
- Printed table of sales summary.
- Bar chart showing revenue by product.
- Saved chart as `sales_chart.png`.

## Interview Questions:
- **How did you connect Python to a database?** Using `sqlite3.connect()`.
- **What SQL query did you run?** SELECT with SUM and GROUP BY.
- **What does GROUP BY do?** Groups rows by a specific column to perform aggregate functions.
- **How did you calculate revenue?** By `SUM(quantity * price)` in SQL.
- **How did you visualize the result?** Using `matplotlib.pyplot`.
- **What does pandas do in your code?** Loads SQL query into a DataFrame for easy analysis and plotting.
- **What’s the benefit of using SQL inside Python?** Automation, integration, and dynamic data analysis.
- **Could you run the same SQL in DB Browser for SQLite?** Yes.

