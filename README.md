# E-commerce Sales Dashboard - Power BI

This project contains an **E-commerce Sales Dashboard** built using **Power BI** to visualize and analyze sales data. The dashboard provides valuable insights into the business performance by representing key metrics using interactive charts and graphs.

## Features
- **Key Performance Indicators (KPIs)**: Displays total orders, revenue, average order value (AOV), and profit.
- **State-wise Sales Analysis**: Visualizes sales distribution across different states.
- **Category-wise and Sub-Category-wise Analysis**: Analyzes sales, quantities, and profits based on product categories and sub-categories.
- **Customer Analysis**: Identifies top customers contributing to the revenue.
- **Payment Mode Analysis**: Displays the preferred payment methods used by customers.
- **Monthly Profit Trend**: Tracks profit variation across months.
- **Quarterly and State-level Filters**: Allows users to filter data for detailed analysis.

## Data Fields
The following data fields are used in this dashboard:

### **Details**
- `Amount`: Total sales amount
- `AOV`: Average Order Value
- `Category`: Product category
- `Order ID`: Unique identifier for each order
- `PaymentMode`: Mode of payment used by customers
- `Profit`: Profit earned from sales
- `Quantity`: Number of products sold
- `Sub-Category`: Specific product sub-category

### **Orders**
- `City`: Customer's city
- `CustomerName`: Name of the customer
- `Order Date`: Date of order placement
- `State`: Customer's state

## Visualizations Used
- **KPI Cards**: For key metrics (Orders, Revenue, Profit, and AOV)
- **Bar Charts**: State-wise sales, Customer sales, Sub-category profit analysis
- **Pie Charts**: Category-wise and Payment mode distribution
- **Column Chart**: Monthly profit analysis
- **Filters**: Quarter-based and state-level filters for refined data exploration

## How to Use
1. Open the Power BI file (.pbix) using **Power BI Desktop**.
2. Navigate through the dashboard to explore various insights.
3. Use the filters to drill down into specific data segments.
4. Analyze the KPIs and graphs to gain business insights.




 **Data Transformation**
- Operations like:
  - **Normalization**: Ensuring data is scaled or standardized for easier comparisons (e.g., normalizing profit by dividing by revenue).
  - **Aggregation**: Using SUM, AVERAGE, or COUNT to get meaningful insights from large datasets.
  - **Calculated Columns**: Creating new columns using `DAX (Data Analysis Expressions)` based on logic (e.g., `Profit = Revenue - Cost`).
  - **Measures**: Dynamic calculations based on filters (e.g., `Total Sales`, `Average Order Value`).

**Data Modeling**
- Relationships between tables using **One-to-Many** or **Many-to-Many** connections ensure proper data interaction.
- Example: `Order ID` might act as a common field between `Orders` and `Details`.

**Column Symbols in the Image**
- The small calculator symbol next to fields like **Amount** and **Profit** indicates **Measures**. Measures are often used for calculations such as sums, averages, or ratios.
- The table icon represents **Columns** — directly from the dataset.
- Hierarchical fields like `Order Date` may have been split into **Year, Quarter, and Month** using `Power Query` for easier analysis.

**Visualization and Reporting**
- After transformation, visual elements like bar charts, pie charts, and KPIs are applied using the cleaned data. Filtering options (e.g., by **Quarter** or **State**) are based on relationships and field transformations.


