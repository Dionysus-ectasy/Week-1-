ShopSmart Retail Sales Analysis (Excel)

AnalystLab Africa Experience Lab | Week 1 | Data Analytics Track | Mission 01 Author: Divine Okezie Nwaoha (Junior Data Analyst)
Project overview

ShopSmart Retail Ltd operates 25 stores across Nigeria and has seen fluctuating sales, inventory shortages and rising product returns. This project cleans the retail data, analyses it in Microsoft Excel, and presents business insights and recommendations.
Folder contents

Week1_Divine_Nwaoha/
├── ShopSmart_Analysis.xlsx     Cleaned workbook: tables, formulas, lookups, pivots, charts, dashboard
├── Executive_Dashboard.pdf     One-page executive dashboard
├── Business_Report.pdf         One-page report: findings, recommendations, risk, opportunity
├── Data_Understanding.pdf      Part 1: datasets, keys and relationships
├── Project_Notes.pdf           Assumptions, limitations and corrections
└── README.md                   This file

Data

Nine CSV files (Customers, Products, Orders, Order_Items, Stores, Returns, Employees, Suppliers, Inventory) and a Data Dictionary. Orders cover 2025.
Workbook guide (ShopSmart_Analysis.xlsx)
Sheet 	Contents
Customers, Products, Orders, Order_Items, Stores, Returns, Employees, Suppliers, Inventory 	The nine cleaned datasets, each an Excel Table
Formulas 	The 10 required KPI formulas, plus Return Rate and Inventory Value
Lookups 	XLOOKUP results: customer name, store name, product name, category, brand, selling price, supplier name
Sales 	Analysis table (one row per order) that feeds the pivots
Pivots 	The pivot tables for Part 5, plus Sales by Region, Return Rate by Category, Most Returned Products, Products per Supplier and Low Stock by Store
Charts 	The six required charts
Dashboard 	Executive dashboard with KPI cards, charts and slicers
Method

    Understood the data: identified primary and foreign keys and mapped the table relationships.
    Cleaned the data: checked for duplicates and missing values (none found), confirmed dates and currency fields were real dates and numbers, converted each dataset into an Excel Table and named the sheets.
    Calculated KPIs with Excel formulas.
    Looked up names and attributes with XLOOKUP across the tables.
    Built pivot tables and charts for sales, returns, suppliers and inventory.
    Answered the business questions and wrote the report.

Key results (Completed orders only)
Metric 	Value
Total Revenue 	₦2,496,824,383
Completed Orders 	16,529
Total Quantity Sold 	49,432
Average Order Value 	₦151,057.20
Average Selling Price 	₦50,364.42
Customers / Products / Stores 	5,000 / 500 / 25
Return Rate 	4.83%
Top category 	Beauty (₦580,991,275, 23.3%)
Top store 	STR003 ShopSmart Lagos (₦113,445,250)
Top region by total sales 	South (₦805,370,701), which has 8 of 25 stores
Peak month 	December (₦224,707,991)
Low-stock products 	21 across 14 stores
Inventory Value (stock at cost price) 	₦3,169,020,818
Assumptions (short version)

    Only Completed orders count; Cancelled and Pending orders are excluded.
    Revenue = Quantity × Unit_Price − Discount. Discount is a flat naira amount. Shipping is excluded.
    Return Rate = Completed orders that were returned ÷ Completed orders.
    Products are linked to suppliers by matching Brand + " Supplies" to Supplier_Name, because Products has no Supplier_ID.
    Stores are identified by Store_ID plus name, because store names repeat.

Known limitations (short version)

    Workbook cells show a $ symbol, but all amounts are Nigerian naira (₦).
    The Top 10 Customers pivot groups by name, so customers who share a name could be combined.
    Pivots are not sorted by default.
    Data covers one year (2025), so seasonality is not confirmed.

The full lists of assumptions, limitations and corrections made during the analysis are in Project_Notes.pdf.
Tools

Microsoft Excel: Tables, XLOOKUP, SUMIFS/COUNTIFS, PivotTables, PivotCharts and slicers.
Links

    GitHub: [add repository link]
    LinkedIn post: [add link]
    X post: [add link]

Submitted to AnalystLab Africa. #AnalystLabAfrica
