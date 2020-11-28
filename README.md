# Tableau-Contoso-DW

# Objectives
Create a Tableau Worksheet (Worksheet 1) with Text Table Visualization based on Contoso DW that shows:
* Sales Quantity and Inventory on Last Day of Period for every month of 2009 (Columns) 
* Across every category hierarchy (Rows)—(Sales Quant on las day)
* Calculate Stock to Sales Ratio and create a new worksheet with line graph visualization 
* Show variation in stock to sales ratio over different months of 2009 across different products categories
* Identify any deviations and use the Drill Down Roll Up operations to identify causes of deviations
* Create a Dashboard w.r.t product categories & sales across cities

# Hints and Calculations
FactInventory Joins:
* Inner join of FactInventory and DimDate: Date Key = Date Key 
* Inner join of FactInventory and DimProduct: Product Key = Product Key
* Inner join of DimProduct and DimProductSubCategory: Product Subcategory Key = Product Subcategory Key
* Inner join of DimProductSubCategory and DimProductCategory: Product Category Key = Product Category Key

Fact Sales Joins:
* Inner join of FactSales and DimDate: Date Key = Date Key 
* Inner join of FactSales and DimProduct: Product Key = Product Key
* Inner join of DimProduct and DimProductSubCategory: Product Subcategory Key = Product Subcategory Key
* Inner join of DimProductSubCategory and DimProductCategory: Product Category Key = Product Category Key

Calculation:
* Use formula SUM([Inventory on Last Day of Period])/SUM([Sales Quantity]) for Stock Sales Ratio

# Repository Content:
* Tableau file for Contoso
* Tableau file for Dashboard
* Data Source
* Word files for respective objectives with explanations
* Screenshots of the results obtained



