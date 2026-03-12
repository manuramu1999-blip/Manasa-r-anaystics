Sales Overview Dashboard Project Documentation:


Executive Summary:


This Sales Overview Power BI project provides a high-level analytical dashboard to monitor and understand an organization’s sales performance. It is designed to centralize key sales metrics and trends in one place, enabling decision-makers to quickly gauge business health. The dashboard integrates sales data (such as orders, units sold, revenue and costs) with customer, product and time dimensions. Using a star-schema data model and DAX calculations, the report delivers concise summaries (e.g. total sales, profit, units) and trend analyses. Interactive visualisations (cards, charts, filters) allow users to explore performance by period, region, product or customer segment. The GitHub repository includes all project assets (data samples, Power BI files, scripts, documentation, etc.) along with clear instructions and guidelines for setup, maintenance and contribution.



Data Sources and Schema:

This project assumes sales-related tables include:

Sales Orders (Fact Table): contains transactional records of each sale (OrderID, Date, CustomerID, ProductID, Quantity, SalesAmount, Cost, etc.).
Date Dimension (Calendar): one row per date with attributes (Date, Year, Month, Quarter, Day, Week, Fiscal flags).
Product Dimension: product attributes (ProductID, Name, Category, Subcategory, etc.).
Customer Dimension: customer attributes (CustomerID, Name, Region, Segment, etc.).
Salesperson or Channel Dimension: (optional) to attribute sales to individual or channel.



Check & Clean the Data (Power Query)

Open Transform Data and verify the dataset.

Things to do:

Remove unnecessary columns

Rename columns properly

Fix data types (date, number, text)

Remove duplicates

Handle null values





Load Data
   ↓
Clean Data (Power Query)
   ↓
Create Relationships
   ↓
Create Measures (DAX)
   ↓
Build Visuals
   ↓
Add Filters / Slicers
   ↓
Design Dashboard
   ↓
Publish Report
