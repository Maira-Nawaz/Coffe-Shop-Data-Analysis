# Coffe-Shop-Data-Analysis

## Coffee Sales Dashboard Overview
This dashboard visualizes sales data for a coffee business, showcasing trends, geographic performance, customer analysis, and product preferences. It integrates various data transformations and Excel features to make the insights interactive and insightful.

## Data Source and Structure
The raw data used for this dashboard included the following columns:

- Order Details: Order ID, Order Date, Product ID, Quantity

- Customer Information: Customer ID, Customer Name, Email, Country

- Product Details: Coffee Type, Roast Type, Size, Unit Price, Coffee Type Name, Roast Type Name

  
- Sales and Loyalty: Sales, Loyalty Card
  
The data was transformed and enriched using formulas like XLOOKUP and INDEX to pull relevant details and maintain consistency.

## Data Processing and Transformations

- Pivot Tables:

Pivot tables were created to summarize sales, customers, and product performance. Metrics such as total sales by country, customer, and product type were computed.

- Data Cleaning:

Columns were cleaned for missing or inconsistent values.
Calculations such as total sales (Sales = Quantity × Unit Price) were verified.

- Formula Usage:

- XLOOKUP: Used for retrieving related data, such as pulling customer details based on Customer ID or product details based on Product ID.
- INDEX and MATCH: Used for dynamic data referencing, such as identifying the roast type name based on size and coffee type.

## Dashboard Components
1. Filters and Controls
Order Date Selector: Allows users to filter data by year, month, or specific time periods.
Roast Type Filter: Enables filtering based on roast preferences (Dark, Light, Medium).
Size and Loyalty Card: Options to refine the data further based on product size and loyalty card status.

3. Total Sales Over Time
A line chart displays monthly sales trends across different coffee types (e.g., Ara, Exc, Lb, Rob).
This visualization helps identify peaks and dips in sales performance.

5. Sales by Country
A horizontal bar chart shows total sales broken down by country (e.g., United States, Ireland, United Kingdom).
This highlights the most profitable regions for the business.

7. Top 4 Customers
Another bar chart ranks customers by total sales, providing insights into the most valuable clients.
Customer names (e.g., Don Fliniff, Brice Romera) and their contributions are highlighted.

## Key Insights

- Sales Trends: Visualizations reveal fluctuations in monthly sales, indicating seasonal demand or promotional impacts.
- Regional Performance: The United States leads in sales, followed by Ireland and the UK.
- Customer Value: Highlighting top customers allows the business to focus on loyalty programs or special offers for high-value clients.

This dashboard combines powerful data processing with clear visual storytelling, making it an effective tool for monitoring and improving coffee sales.
