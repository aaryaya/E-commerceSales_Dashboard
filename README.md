# Aarya's E-Commerce Sales Dashboard

This repository contains a Power BI dashboard that provides key insights into an e-commerce sales dataset. The dashboard highlights various metrics such as total sales amount, quantity sold, total profit, and average order value. It also offers an interactive experience through filters and various visualizations.

## Dashboard Overview

### Key Metrics
- **Total Sales Amount**: ₹438K
- **Total Quantity Sold**: 5615 units
- **Total Profit**: ₹37K
- **Average Order Value (AOV)**: ₹121K

### Visualizations
1. **Amount by State**: Displays the total sales amount segmented by different states.
2. **Amount by Customer ID**: Breaks down the total sales amount by individual customer IDs.
3. **Quantity by Category**: Shows the quantity sold for each product category.
4. **Quantity by Payment Mode**: Displays the distribution of quantities sold based on different payment methods.
5. **Profit by Month**: Highlights the profit trends across various months.
6. **Profit by Sub-Category**: Breaks down the profit by specific product sub-categories.

### Filters
- **Quarter Filter**: Allows users to filter the data based on quarters (Q1, Q2, Q3, Q4).
- **State Filter**: Users can filter the data by specific states.

## Data Sources

1. **orders.csv**
   - Columns: `Order ID, Order Date, CustomerName, State, City`
   - This file contains order-level details, including customer names, locations (state and city), and order dates.

2. **details.csv**
   - Columns: `Order ID, Amount, Profit, Quantity, Category, Sub-Category, PaymentMode`
   - This file provides the transactional details of each order, including the amount, profit, quantity, product category, and payment method.

## How to Use the Dashboard

1. Download the `.pbix` file from the repository.
2. Open the file in Power BI Desktop.
3. Interact with the dashboard by using the filters for quarters and states.
4. Explore the different charts and metrics to gain insights into the e-commerce sales data.
5. Ensure the `orders.csv` and `details.csv` files are accessible in the same directory as the `.pbix` file, or update the file paths in Power BI to point to your dataset location.


## Files in this Repository

- **ecommercedashboard.pbix**: The Power BI dashboard file containing all the visualizations and data models.
- **orders.csv**: CSV file with order-level details.
- **details.csv**: CSV file with transactional details.
- **connection_info.txt**: Contains connection details used in the dashboard.
- **ecommercedashboard_screenshot.png**: Contains a screenshot of the dashboard
  
## License
This project is open to all and is released under a permissive license. You are free to use, modify, and distribute the work without copyright restrictions.

## Author
- **Aarya Shirbhate**  
  Data enthusiast with a passion for creating impactful visualizations and deriving insights from data.


