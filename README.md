Amazon  Diwali Sales E-Commerce Data Analysis-2025
Project Overview:
              This Project focuses on analysing Amazon Diwali sales data to understand product-wise and category-wise sales performance. The analysis aims to identify top-performing products, overall sales distribution, and demand patterns using data visualization techniques.
Objective Of the Project:
	To analyse total sales across different products.
	To identify top-performing products during the Diwali sale.
	To understand category-wise quantity distribution.
	To provide business insights using visualizations.

Dataset Description:
	Dataset Name: Amazon Diwali Sales Dataset
	Data Source: Kaggle (Online Dataset)
	Key Fields Used:
1.	Product Name
2.	Category
3.	Sales Amount
4.	Quantity
Tools Used:
	Microsoft Excel
	Microsoft Power BI
	Microsoft Word (for documentation)
Data Cleaning & Preparation:
   The Raw dataset contained inconsistencies, formatting issues, and unstructured fields. Excel was used as the primary tool for cleaning and preparing the data before visualisation.
	Data Cleaning: 
	Removed duplicate order records to prevent inflated sales values.
	Identified and handled missing values in columns such as Delivery Status and Ratings.
	Corrected spelling inconsistencies in State and Product Category fields.
	Standardized text using Proper Case and trimming extra process.
	Data Transformation:
	Date Handling: Extracted Month from the Date column for time-based analysis.
	Column Splitting: Separated month values from Date.
	Column merging: Combined State and Country into a single Location field.
	Currency Formatting: Converted Unit Price and Total Sales into INR format

	IF Conditions:  
	Classified sales as High Value or low value.
	Categorized review ratings as Good, Average, or poor.
	COUNTIF logic:
	Identified Repeat Customers and New Customers
	Conditional Formatting:
	Data bars for Total Sales.
	Colour scales for Quantity.
	Icon sets for Review Ratings.
These steps ensured accuracy, consistency, and improved readability of the dataset.

Pivot Table Analysis (Excel)
Pivot Tables were used to summarize and analyse large volumes of sales date efficiently.
	Category-wise Sales Analysis:
	Aggregated Total Sales by product Category.
	Helped identify top-performing and low-performing categories.
	Monthly Sales Trend Analysis:
	Analysed Total Sales on a month-wise basis.
	Observed increased sales during the Diwali festive period.
	State-wise Sales Analysis:
	Compared sales performance across different states.
	Identified states with the highest revenue contribution.



 
 

Power BI Dashboard & Visualisations:
After completing data preparation in Excel, the dataset was imported into Power BI for advanced analysis and visualisation.

This project uses a single-table (flat data model) approach. Since all required fields (sales, product, customer, state, date, payment, delivery status) were available in one cleaned dataset, no additional dimension tables or complex relationships were required.
	Cleaned Excel dataset directly imported into Power BI
	All calculations performed using measures on a single fact table
	Flat model chosen to keep analysis simple and efficient.
	All KPI’s and calculations were created using measures on the same dataset.
Future Enhancement: In future iterations, the model can be enhanced by creating a star schema:
	Fact _Sales Table (Order Id, Sales, Quantity, Date ID)
	Dim_ Product
	Dim_ Customer
	Dim_ Date
	Dim_ State

KPIs:
	Total Sales:1.12 billion
	Total Quantity Sold:45k
	Total Reviews: 46k
Visuals used:
	Sales by Product Category (Bar Chart)
	Sales Trend by Day (Line Chart)
	Top Product by Sales
	State-wise Sales (Map visual)
	Payment Method Distribution (Donut chart)
	Delivery Status Analysis
	Quantity by Category (Tree Map)







 



 

Slicers:
	Product Category
	State
Key Insights:
	Total sales were highest during the festive period, indicating strong seasonal demand
	Electronics and Fashion categories contributed the majority of overall revenue.
	A few top states generated most of the sales, showing regional concentration.
	Online payment methods were used more frequently compared to cash on delivery.
	Orders with successful delivery status showed higher sales value than cancelled or returned orders.
Conclusion:
	This analysis provides a clear understanding of sales performance across products, regions, and time.
	The dashboard helps identify top-performing categories, customer purchase behaviour, and regional trends.
These insights can support better business decisions related to inventory, planning, marketing strategy, sales growth.
           

