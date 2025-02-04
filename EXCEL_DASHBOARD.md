📊 [Project Title] - Excel Data Analysis
📌 Overview
This project analyzes an order dataset containing transactional details, including customer orders, sales figures, and shipment statuses. The objective is to clean, format, visualize, and create an interactive dashboard using Microsoft Excel for better business insights.

📂 Dataset Details
File: order_data.xlsx
Source: [Custom sales and order dataset]
Columns:
Order_Line_Number: Sequence number for the order line.
Sales: Total sales amount for the order line.
Days: Transaction or shipment date.
Status: Current status of the order (e.g., "Shipped," "OnHold").
Quantity_Order: Quantity of items ordered.
Month_ID: Numeric ID representing the month of the transaction.
Year_ID: Year of the transaction.
Product_Line: Product category (e.g., "ClassicCars," "Planes").
MSRP: Manufacturer's Suggested Retail Price for the product.
Product_Code: Unique code for the product.
Customer_Name: Name of the customer placing the order.
Phone: Customer's phone number.
Address: Primary address of the customer.
Address_2: Additional address details (if any).
City: City where the customer resides.
State: State where the customer resides (if applicable).
Postal_Code: Postal code for the customer's location.
Country: Country of the customer.
Territory: Business territory for categorization.
A: [Unclear field, to be defined during analysis].
Deal_Size: Size of the deal based on sales (e.g., "Large").
🔧 Steps Taken
1️⃣ Data Cleaning
Removed duplicates using Excel’s Remove Duplicates feature.
Reformatted the Sales column to standard numeric format for analysis.
Standardized date formats in the Days column to DD/MM/YYYY.
Addressed missing data using formulas like:
excel
Copy
Edit
=IF(A2="", "Unknown", A2)  
2️⃣ Data Formatting
Applied conditional formatting to highlight:
Orders with "OnHold" status.
High-value deals in the Sales column.
3️⃣ Visualization
Created charts and graphs to analyze:
Sales trends by Product_Line and Deal_Size.
Order volume by Country and Territory.
4️⃣ Interactive Dashboard
Built a dynamic dashboard using Pivot Tables and Slicers to explore:
Customer buying patterns.
Shipment statuses by region and product type.
🚀 Insights
[Highlight key findings, e.g., which product lines generate the highest sales, most frequent order statuses, etc.]
📈 Tools Used
Microsoft Excel
Excel formulas and functions
Pivot Tables and Charts
