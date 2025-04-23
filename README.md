# Sales-Performance-Analysis
The Sales Performance Analysis project aims to analyze historical sales patterns, customer behavior, and product performance. Using SQL for data extraction and transformation and Power BI/Tableau for visualization, this project will provide insights into sales trends, regional performance, and customer segmentation.
## Dataset Details
Dataset Name: Financial Reporting and Analysis
Dataset Link: Click Here for CSV File or XLSX File
Total Records: 2824
Columns Overview:
1. Order Information:
● ORDERNUMBER – Unique identifier for each order
● QUANTITYORDERED – Number of units purchased
● PRICEEACH – Unit price of the product
● ORDERLINENUMBER – Line item number within an order

● SALES – Total sale amount
● ORDERDATE – Date when the order was placed
● STATUS – Order status (Shipped, Pending, etc.)
2. Product Information:
● PRODUCTLINE – Category of the product
● MSRP – Manufacturer’s Suggested Retail Price
● PRODUCTCODE – Unique product identifier
● DEALSIZE – Deal classification (Small, Medium, Large)
3. Customer Information:
● CUSTOMERNAME – Name of the customer
● PHONE – Contact number
● ADDRESSLINE1, ADDRESSLINE2 – Customer address details
● CITY, STATE, POSTALCODE, COUNTRY – Customer location
● TERRITORY – Sales region
● CONTACTLASTNAME, CONTACTFIRSTNAME – Contact person’s name

## Task to be Performed
Task 01: Data Preparation & SQL Setup
✔ Load the dataset into SQL (MySQL/SQL Server)
✔ Create structured tables with relationships
✔ Validate and clean the data:
● Handle missing values
● Convert date formats
● Create calculated fields
● Ensure proper data types
Task 02: Exploratory Data Analysis (EDA) using SQL & Power BI/Tableau
📌 Option 1: Performing EDA using SQL
Using SQL, we can explore the dataset, perform aggregations, and generate insights.
✔ Identify top-selling products
✔ Analyze sales trends over time
✔ Identify seasonal sales patterns
✔ Perform territorial sales analysis

📌 Option 2: Performing EDA using Power BI/Tableau
EDA can also be done using Power BI or Tableau, where we can explore trends and insights
visually.
✔ Load the SQL query output into Power BI/Tableau
✔ Perform KPI analysis (Total Sales, Avg Order Value, Customer Count)
✔ Create trend analysis charts (monthly sales, YoY growth)
✔ Build customer segmentation models
Recommended Visualizations:
📊 Sales Trends Over Time (Line Chart)
📈 Top 10 Products by Revenue (Bar Chart)
📍 Geographic Sales Distribution (Map Visualization)
📊 Customer Segmentation (High-Value vs Low-Value Customers) (Pie Chart)

Task 03: Power BI/Tableau Dashboard Implementation
Dashboard 1: Sales Overview
✔ Year-to-Date (YTD) Sales KPIs
✔ Monthly Sales Trend Analysis
✔ Territory-wise Sales Breakdown
✔ Product Line Distribution
Dashboard 2: Customer Analysis
✔ Customer Segmentation (High vs Low Spenders)
✔ Geographic Sales Distribution
✔ Order Frequency Patterns
✔ Customer Lifetime Value Calculation
Dashboard 3: Product Performance
✔ Top-Selling Product Lines
✔ Inventory Turnover Analysis
✔ Price Point Analysis
✔ Seasonal Product Sales Trends

Task 04: Advanced Analysis with DAX & Time Intelligence
✔ Create DAX measures for advanced calculations
✔ Implement time intelligence in Power BI
✔ Perform trend forecasting & seasonality detection

Task 05: Report Development & Business Insights
✔ Executive Dashboard
● High-level KPIs & insights
● Sales growth trends
● Customer & product performance summaries
✔ Operational Reports
● Daily/Monthly Sales Reports
● Inventory & Stock Management
● Regional/Territory Performance
