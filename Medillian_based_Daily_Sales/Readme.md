# Medallion Architecture with Databricks and Tableau📉

## Overview

This project implements the Medallion Architecture using Databricks, structuring data into Bronze, Silver, and Gold layers to facilitate efficient data processing, transformation, and business intelligence visualization in Tableau.

## Architecture Breakdown

### Bronze Layer🥉(Raw Data Ingestion)

The Bronze layer consists of raw data ingested from multiple sources, including transactional databases, APIs, and streaming data sources. This layer stores unprocessed data in its original format, ensuring data availability for further processing.

### Silver Layer🥈(Cleansed and Transformed Data)

The Silver layer refines and structures the raw data by performing data cleansing, deduplication, and enrichment. It integrates data from various sources to create a consistent and usable dataset.

### Gold Layer🥇(Business Aggregations and Analytics)

The Gold layer contains aggregated and business-ready data optimized for reporting and visualization. It enables efficient querying and analysis.

#### Business Queries in Gold Layer

- Category Sales Analysis

    - Aggregates total sales for each product category by joining order data with product information from the Silver layer.

    - Helps understand revenue distribution across different product categories.

- Daily Sales Trend

    - Computes daily total sales transactions, providing insights into sales trends over time.

    - Useful for monitoring revenue performance and identifying seasonal patterns.

### Data Visualization with Tableau

- The business insights generated in the Gold layer are visualized using Tableau to facilitate data-driven decision-making. The key dashboards include:

- Category Sales Dashboard: Displays sales performance by product category, helping stakeholders identify top-selling categories.

- Daily Sales Trend Dashboard: Provides a time-series visualization of daily sales, assisting in trend analysis and forecasting.

** Unfortunately, I lost my visualization in my older Free Trail Account. I will try to connect with new account to my golder layer in Databricks and update to show the visualization **

### Tools Used

- Databricks: For data processing and transformation.

- Apache Spark: For distributed data processing.

- Tableau: For business intelligence and data visualization.


#### Contact

For any queries or discussions/suggestions, feel free to reach out to me on LinkedIn: https://www.linkedin.com/in/raja-ranjith-kumar-asileti-2375a514a/