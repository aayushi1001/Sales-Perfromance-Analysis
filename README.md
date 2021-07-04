# Sales-Perfromance-Analysis

Problem Statement : 

Objective

To build a dashboard that will present monthly sales performance by product segment and product category to help client identifying the segments and categories that have met or exceeded their sales targets, as well as those that have not met their sales targets. 

Domain: Ecommerce

Dataset Description

We will be using two datasets here i.e. Sample - Superstore and Sales_Target.

* Sample -Superstore which covers Orders data from 2014 - 2017;

Within this file you will find the following fields:

Field 	Description 
Row ID	Observation Index
Order ID	Unique Order ID of a product
Order Date	Order Placement Date
Ship Date	Shipment Date of the placed order
Ship mode	Shipment mode of the placed order
Customer ID	Unique Customer ID
Customer Name	Name of the Customer
Segment	Product Segment (i.e.HomeOffice/Corporate/Consumer etc.)
Country	Unique Country Name
City	Unique City Name
State	Unique State Name
Postal Code	Area wise Postal code
Region	Especially the part of a country
Product ID	Unique Id respective to Product
Category	Product category
Sub-Category	Product Subcategory
Product Name	Unique Product Name
Sales	Sales Amount
Quantity	The amount or number of a material
Discount	A deduction from the usual cost of something
Profit	Obtain a financial advantage or benefit

 Sales-Target will cover the target data;


Within this file you will find the following fields:

Field 	Description
Category	Product category
No. of Records	Unique Record
Order Date	Order Placement Date
Sales Target	Targeted Sales to be achieved 
Segment	Product Segment (i.e.HomeOffice/Corporate/Consumer etc.)
 







Problem Solving Approach :

The Saved Sample – Superstore dataset is used. 

A bullet chart with Category and Segment dimensions and Sales measures is created. 

The data is then blended with the Saved Sample - Sales Target data set to bring in the Sales Target measure. 

The charts are color coded to identify Categories and Segments that are above or below target. 

The year of sales is added to the view to identify trends and outliers. 

A filter is added so that the user can select one, more than one, or all years. 

A dashboard is created with this view.
