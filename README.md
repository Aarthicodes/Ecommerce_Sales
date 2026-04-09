# Ecommerce_Sales
# Project Objective: 
	The objective of the analysis is to understand sales performance, Customer behavior, Product trends and regional contribution to revenue.
	The study uses data modeling, pivot tables, charts, slicers and key performance indicators (KPI) to derive meaningful insights.

# Dataset Description: 
The dataset follows a star schema model, consisting of one fact table and multiple dimension tables.
Fact Table:
	Sales_Fact: Contains transactional data such as Order ID, Order Date, Sales Amount, Quantity, Product ID, Customer ID, Store ID
Dimension Tables
	Customer_Dim: Customer ID, Loyalty Level, Region
	Product_Dim: Product Name, Category, Sub_Category
# Data Cleaning and Preparation:
	Removed blank and duplicate rows
	Corrected inconsistent text and date formats
	Converted Sales amount into currency format and Quantity were numeric
	Standardized column names
	Handled missing values using appropriate formulas
	Used Trim and clean function to clean the data and used proper data to standardized the text
	Store_Dim: Store Type, State.
# Pivot Table Analysis:
Sales by product category:
         This analysis highlights which product categories contribute the most to total revenue.
Revenue by State:
         Identities top-performing states and regional sales distribution.
Customer count by Loyalty:
        Analyzes customer distribution across loyalty tiers.
Product-wise sales:
	Certain Product categories generate the highest revenue.
	Clothing and Home products show moderate sales performance
	Beauty products have comparatively lower sales, Suggesting potential for promotional strategies
Category count Distribution:
	Beauty products have highest distribution in sales products
	Electronics and Home appliances are fairly distributed
	Clothing and beauty have comparatively lowest sales. 
Regional Contribution:
	Flagship Stores (North and East) account for the largest portions of total sales
	South and West Flagship stores Contribute less, highlighting regional performance differences.
	Online (South and East) account for the largest portions of total sales
Customer Loyalty Level:
	Gold and Platinum customers form a significant portion of the customer base
	This indicates strong customer retention and loyalty
	Sliver and Bronze segments still offer growth potential through engagement offers.
# Conclusion
 The sales analysis reveals that overall business performance is strong, with the East and North region based on Flagship where as Based on Online East and South performance are maximum when compared to other region. The sales need to improve in West region for betterment of the sales. Electronics and sports categories emerge the top performance segments, while other category maintains balanced participation.
To further enhance growth, the business can focus in west region to strengthen the lower performance and also converting the Silver and Bronze customer into higher loyalty tiers.

Compares performance between online and physical store types.

