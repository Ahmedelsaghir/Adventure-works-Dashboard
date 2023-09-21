# Adventure-works- Sales Dashboard
Summary of project objectives:
I'm was working on transforming, Analyzing, modeling and visualizing the Adventure Works history data of sales and operations departments to figure out the company's performance to get an overview insights of the both department's sales performance of the previous years to know the gaps and how we can keep the market equity and expand more.


![1](https://github.com/Ahmedelsaghir/Adventure-works-Dashboard/assets/69742253/a33c000f-7fa2-42e0-a0e8-ef33cc542636)



![2](https://github.com/Ahmedelsaghir/Adventure-works-Dashboard/assets/69742253/667e0040-bdd2-4e04-9342-65b7a5289a53)



![1 1](https://github.com/Ahmedelsaghir/Adventure-works-Dashboard/assets/69742253/d6c74f84-86dc-48ed-a429-6e3df70ef1d1)



![fliter](https://github.com/Ahmedelsaghir/Adventure-works-Dashboard/assets/69742253/5c69729e-ff22-42a4-8707-05288096d59d)



![3](https://github.com/Ahmedelsaghir/Adventure-works-Dashboard/assets/69742253/f9190082-51cf-4cc2-9a40-0056bea9e74b)


Tables:
Conductivity Mode => Direct Query
- Sales.SalesOrderHeader
- Sales.SalesOrderDetail
- Sales.vSalesPerson (view)
- Sales.SalesTerritory
- Purchasing.ShipMethod
- Production.Product
- Production.ProductSubcategory
- Production.ProductCategory
- Status (Add based on ufnGetSalesOrderStatusText function)
- Dates (Created table y Power Query)
- Get all into one product table (Merge M Language)
(Contains: PorductID, Product, SubCategory, Category)


![schema](https://github.com/Ahmedelsaghir/Adventure-works-Dashboard/assets/69742253/a978071a-eccb-47f1-93b6-f5e43f4dfa22)

Modeling:

- Build a Star Schema 
- Product Hierarchy
- Date Hierarchy

Measures
- Total no. of Orders Measure 
- Total SubTotal Measure 
- Total Tax Measure 
- Total Freight Measure 
- Total Due Measure 
- Total no. of Qty Measure 
- Total no. of Products Measure 
- Create DAX table that contains all measures

Visuals:
- Drill Down
- Drill Through 
- Tooltip page
- Bookmark
- Total No. of Orders Card
- Total SubTotal Card
- Total Tax Card
- Total Freight Card
- Total Due Card
- Total no. of Orders by Order Date vs. Ship Date vs. Due Date
- Total no. of Orders by Status
- Total no. of Orders by Ship method
- Total no. of Orders by Category, SubCategory, Product
- Total no. of Orders by Flag Online & Offline
- Total no. of Orders vs. Total Due by Territory
- Top 10 Salesmen by Subtotal
- Subtotal by year
- Subtotal Salesmen
- Total Due vs orders by territories
- Top 10 products by subtotal

AdventureWorks
- Data Source: OLTP
https://lnkd.in/dkMpPQqC
