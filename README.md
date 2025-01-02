# Pizza Sales Dashboard ( Interactive Dashboard Creation Using Microsoft Excel)

## Project Overview

This project involves analyzing pizza sales data to gain insights into the business performance of a pizza restaurant. The primary goal is to calculate key performance indicators (KPIs) and create visualizations to help identify trends in customer preferences, peak ordering hours, and best-selling pizzas. The dataset consists of approximately **48,500 records** and is analyzed and visualized using Microsoft Excel.
# Dataset used
- <a href = "https://github.com/Sahil302002/Pizza_Sales_Analysis/blob/main/pizza_sales%20excel%20file.xlsx" > Dataset</a>


## Data Processing

1. **Data Cleaning and Transformation**:
    - Pizza sizes (M, L, S, XL) were standardized to full descriptions (Medium, Large, Small, X-Large) using Excel’s Find and Replace functionality.
    - A new column for `Order's Day` was added, which labels the weekday for each order, allowing for analysis of weekly sales trends.
2. **Unique Order Count**:
    - To calculate the total number of distinct orders, I used Excel's `COUNTIF` function to count unique order IDs and then applied a summation technique to identify the total number of unique orders.


## Key Performance Indicators (KPIs)

The following metrics have been calculated to gain insights into the business:

1. **Total Revenue**: The sum of the total price of all pizza orders.
2. **Average Order Value**: The average amount spent per order, calculated by dividing total revenue by total orders.
3. **Total Pizzas Sold**: The sum of the quantity of all pizzas sold.
4. **Total Orders**: The total number of orders placed.
5. **Average Pizzas per Order**: The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.


## Visualizations

The project includes several visualizations that highlight key trends in the pizza sales data:

1. **Daily Trend for Total Orders**: A bar chart that shows daily trends in the total number of orders placed.
2. **Hourly Trend for Total Orders**: A line chart that displays the hourly trends in order volumes, helping identify peak ordering times.
3. **Percentage of Sales by Pizza Category**: A pie chart showing how sales are distributed across different pizza categories.
4. **Percentage of Sales by Pizza Size**: A pie chart representing the percentage of sales for each pizza size (Small, Medium, Large, X-Large).
5. **Total Pizzas Sold by Pizza Category**: A funnel chart that compares the total number of pizzas sold across different pizza categories.
6. **Top 5 Best Sellers by Total Pizzas Sold**: A bar chart showcasing the top 5 best-selling pizzas based on the number of pizzas sold.
7. **Bottom 5 Worst Sellers by Total Pizzas Sold**: A bar chart showing the bottom 5 worst-selling pizzas based on total sales.

# Dashboard View 
 - <a href = "https://github.com/Sahil302002/Pizza_Sales_Analysis/blob/main/Pizza%20Dashboard.png">Dasboard</a>

## Tools Used

- **Microsoft Excel**: Excel was used to clean, process, analyze, and visualize the pizza sales data. It includes functions such as `SUM`, `AVERAGE`, `COUNTIF`, and Excel’s charting features to create insights and reports.
- **Excel Charts**: Various types of charts were used to visually represent the data, including bar charts, line charts, pie charts, and funnel charts.
