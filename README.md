# Online-Retail-Dashboard

# Introduction

This project involves creating an interactive sales dashboard using Microsoft Power BI to provide comprehensive insights into online retail sales performance from multiple perspectives. The dashboard will utilize real-time data visualizations, enabling users to explore various metrics and make data-driven decisions.

# Objectives

The primary goal is to analyze online retail sales data effectively and provide strategic insights through a user-friendly and interactive Power BI dashboard interface. This will help optimize decision-making for sales performance, customer segmentation, and product analysis.

#  Process Overview

1. **Data Preparation:**

    * **Data Import and Transformation:** Utilized Power BI's Power Query to import the dataset, clean, and transform the data, such as splitting columns like invoice date and time for better analysis.
      
    * **Calculations and Enhancements:** Created a new column to calculate the total transaction amount by multiplying the quantity and unit price. Added relevant measures like the customer lifetime value and aggregated metrics like total revenue, profit, and order count.
      
    * **Data Model:** Organized the dataset into fact and dimension tables (customer, product, invoice) to optimize analysis. Introduced a date table to enable time-based calculations.

2. Building the Data Model:

    * Create Relationships: Establish relationships between columns (e.g., Orders, Products, Customers ID).
      
    * Date Table: Developed a custom date table to analyze metrics over various periods (daily, monthly, quarterly, etc.).
      
    * Create Hierarchies: Create hierarchies for dimensions like Date, Product Category, and Customer Geography.

3. Calculating Key Metrics:

    * DAX Calculations: Used Data Analysis Expressions (DAX) to compute key performance indicators (KPIs) such as:
      
        * Total Revenue: Sum of quantity multiplied by unit price.
          
        * Total Orders: Count of distinct invoice numbers.
          
        * Average Order Value: Total revenue divided by total orders.
          
        * Top Products: Based on revenue and quantity sold.
          
        * Customer Segmentation: Categorized customers by spending levels or geographic location (country).

3. Dashboard Design:

    * Interactive Elements: Added slicers for time (year, quarter, month), product categories, and customer location to allow dynamic filtering and exploration of the data.

    * Data Visualizations: Created various custom charts such as:

    * Line charts for tracking revenue trends over time.

    * Bar charts to visualize top-selling products or countries with the highest sales.

    * Maps to display geographic sales distribution.

    * Conditional Formatting: Applied conditional formatting to highlight important trends, outliers, and KPIs that deviate from the norm (e.g., peak sales days, product performance).
  
**Tools Used**

Excel: For data cleaning
SQL: Running queries and answering business questions.
Power Query: For data cleaning and transformation.
Power BI: For data visualization and building interactive dashboard elements.

# Conclusion

The interactive online retail dashboard in Power BI provides valuable insights into sales performance, enabling data-driven decision-making. Power BI's tools such as Power Query, DAX, and advanced visualization capabilities offer a dynamic and intuitive interface for analyzing online retail sales effectively.

# Insights from Dashboard Charts

* Customer Analysis: Identify top customers based on total spending, order frequency, and country for targeted marketing campaigns.

* Revenue Trends Over Time: Analyze weekly and monthly sales trends to identify seasonal patterns and spikes.

* Sales by Month: Determine peak sales Month to optimize staffing, marketing, and operational strategies.
  
* Product Performance: Understand which products drive the most revenue and which underperform to enhance inventory and pricing strategies.

* Country-Level Sales: Evaluate sales performance by country to tailor marketing and expansion strategies to top-performing regions.

* Monthly and Quarterly Performance: Track sales against targets for informed decision-making monthly and quarterly.


