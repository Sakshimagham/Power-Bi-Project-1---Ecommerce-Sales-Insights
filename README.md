# Power-Bi-Project-1---Ecommerce-Sales-Insights

## Ecommerce Sales Dashboard
A comprehensive sales dashboard for ecommerce businesses, integrating data from two tables: Orders and Details.

# Overview
This dashboard provides insights into ecommerce sales data, enabling businesses to make informed decisions. The dashboard integrates data from two tables: Orders and Details.

# Dataset
The dataset consists of two tables:

Orders([Details - Details.csv](https://github.com/user-attachments/files/17903156/Details.-.Details.csv))

Contains information about each order, including:
- ID: Unique order identifier
- Order Date: Date the order was placed
- Customer Name: Name of the customer who placed the order
- State: State where the order was shipped
- City: City where the order was shipped

Details([Orders - Orders.csv](https://github.com/user-attachments/files/17903162/Orders.-.Orders.csv))

Contains detailed information about each order, including:
- ID: Unique order identifier
- Amount: Total amount of the order
- Profit: Profit made on the order
- Quantity: Number of items ordered
- Category: Category of the product ordered
- Sub-Category: Sub-category of the product ordered
- Payment Mode: Payment method used by the customer

  

# PowerBi Visualization :

![Screenshot 2024-11-25 183349](https://github.com/user-attachments/assets/722e8e80-28ba-4a3e-a408-04b677f5a1ca)

The dashboard features the following visualizations:
Slicer
- Sum of Profit: Total profit made across all orders
- Sum of Amount: Total amount of all orders
- Sum of Quantity: Total number of items ordered
These slicers enable users to filter the data by different criteria, such as date range, customer segment, or product category.

Bar Chart
- Sum of Profit by Sub-Category: Total profit made by each sub-category
This bar chart helps identify which sub-categories are generating the most profit.

Donut Chart
- Sum of Amount by State: Total amount of orders by each state
This donut chart provides a visual representation of which states are generating the most revenue.

Treemap
- Sum of Profit and Sum of Quantity by Category: Total profit and quantity of orders by each category
This treemap helps identify which categories are generating the most profit and quantity.

Filled Map
- State and City: Geographical representation of orders by state and city
This filled map provides a visual representation of where orders are coming from.

# Purpose

The purpose of this dashboard is to provide ecommerce businesses with a comprehensive view of their sales data. By integrating data from two tables, this dashboard enables businesses to:
- Identify trends and patterns in sales data
- Analyze the performance of different products, categories, and sub-categories
- Understand the geographical distribution of orders
- Make informed decisions about inventory management, marketing strategies, and sales forecasting
