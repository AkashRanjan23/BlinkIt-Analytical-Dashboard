
![SnapSave io-BlinkitLogoAnimation_Stompy-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/e44d49b4-76f1-4ad5-8d7f-d87480498291)

# BlinkIt Sales Analysis Dashboard

## Project Overview

The **BlinkIt Sales Analysis Dashboard** is an interactive business intelligence solution created using **Power BI**. The dashboard provides an in-depth analysis of sales performance, outlet metrics, and product-level insights to support decision-making processes in retail. This project showcases the power of data visualization for optimizing business strategies.

## Features

- **Total Sales Analysis:** Displays overall revenue generated across different outlets.
- **Item-wise Sales Breakdown:** Provides detailed insights into sales performance by product category.
- **Outlet Performance:** Highlights sales trends based on outlet location, size, and type.
- **Average Sales & Ratings:** Displays metrics on sales performance and customer feedback.
- **Time Series Analysis:** Tracks outlet establishment over time with sales growth trends.
- **Filter Panel:** Offers dynamic filtering options for Outlet Location, Size, and Item Type to enhance data exploration.

## Tech Stack

- **Power BI:** For creating interactive and insightful data visualizations.
- **Power Query:** For data cleaning and transformation.
- **DAX (Data Analysis Expressions):** For advanced calculations and measures within the dashboard.

## DAX Measures Used

- **Total Sales:** `SUM(SalesData[Sales])`
- **Average Sales:** `AVERAGE(SalesData[Sales])`
- **Total Items Sold:** `SUM(SalesData[ItemCount])`
- **Average Rating:** `AVERAGE(SalesData[Rating])`

## Project Workflow

1. **Data Cleaning:** Used Power Query to clean and transform raw sales data for consistency.
2. **Data Modeling:** Built relationships between data tables and created calculated columns for analysis.
3. **Dashboard Creation:** Developed an interactive dashboard with dynamic filters for insightful data exploration.
4. **Visualizations:** Utilized bar charts, line graphs, and pie charts to present actionable insights.
   
## Insights & Recommendations

- **Top Performing Outlets:** Outlets in **Tier 3 locations** generated the highest sales, suggesting a focus on underserved areas.
- **Product Performance:** **Fruits & Snacks** emerged as the best-selling items, recommending expansion in this category.
- **Sales Trends:** A noticeable decline in sales was observed post-2018, indicating the need for targeted promotional strategies.

## How to Use

1. Clone or download the repository.
2. Open the **Power BI (.pbix)** file to interact with the dashboard.
3. Explore different insights using filters for Outlet Location, Size, and Item Type.

## Conclusion

This project highlights how Power BI can be leveraged to visualize and analyze sales data, enabling businesses to make data-driven decisions for improving outlet performance and product strategy.
