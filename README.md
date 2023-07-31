# Sales-Data-Analysis

Assemble a sales reports with different visuals to best show the Sales Insights in one page Dashboard.
Steps:
1-Data Gathering / Requirement:
-Sales (folder by year)
-Categories (Excel)
-Geography (Excel)
-Product (CSV)
-SalesRep (Excel)
-SubCategories (Excel)

2-Data Modeling: 
Task 2.1:the respective transformations to the Sales fact table in order to split the Country form the City in field “Location”. Making sure you set up the correct Data Type to allow Geo maps.
Task 2.2: Created unique key (GeoKey) in Sales and Geography table
Task 2.3:Created a small function that removes the “ID - ” part of these columns that you can invoke and reuse for these two queries to clean the IDs.
Task 2.4:Create the Data Model connecting all tables and using the Calendar table already set up in the pbix.

3-DAX calculations:
Task 3.1: Calculate Total Revenue in Sales table, using the Product’s Retail Price, and multiplying it by the Units.
Task 3.2: Calculate Total Cost in Sales table, using the Product’s Standard Cost, and multiplying it by the Units
Task 3.3: Calculate Gross Profit in Sales: Total Revenue – Total Cost
Task 3.4: Calculate a Gross profit MoM growth Change% measure that could benefit us in decision making
Task 3.5: Calculate a measure for AVG sales per day – this is the average sum of Total Revenue per day based on the Dates of actual Sales.
Task 3.6: Breakdown Analysis by Product (drop or increase) (USED WATERFALL CHART)
Task 3.7: Calculate the following time measures:
this is QBR Report. So QoQ Growth is required.Assemble a sales reports with different visuals to best show the Sales Insights in one page Dashboard. Steps: 1-Data Gathering / Requirement: -Sales (folder by year) -Categories (Excel) -Geography (Excel) -Product (CSV) -SalesRep (Excel) -SubCategories (Excel) 
