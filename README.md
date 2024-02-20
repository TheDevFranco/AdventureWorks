# AdventureWorks PowerBI Project

## Problem Statement

This project comes from the Microsoft SQL database sample data sets. The main idea behind the project is to create a sales dashboard for a company, that allows you to filter by year, month, product, among others. 

Due to Power BI licensing limitations, I can't share the web dashboard, however, I am uploading the .pbix file so you can download it and check the data.

### Steps followed 
- Step 1: Downloaded the most recent version of the AdventureWorksDW20XX.bak from the link: : https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms
- Step 2: Loaded the data into SSMS
- Step 3: Cleaned the data (data types, NULLS, etc). DB has dimensions and facts tables.
- Step 4: Queried the data needed for the analysis: DimCalendar, DimCustomer, DimProduct and FactInternetSales
![sqlquery](https://github.com/TheDevFranco/AdventureWorks/assets/94664155/e1163803-8386-4889-abb0-c86d5a3bb199)

- Step 5: Exported 4 tables as CSV Files 
- Step 6: Importad data to Power BI; added a 5th table including marketing budget historical data
- Step 7: Defined relationships between tables
![adventureworksrelationshiptables](https://github.com/TheDevFranco/AdventureWorks/assets/94664155/011c9ad0-3504-438f-b004-7a29d845f85a)
- Step 8: Created dashboard

![Screenshot 2024-02-19 200552](https://github.com/TheDevFranco/AdventureWorks/assets/94664155/172ef28d-bb1c-4e9d-bd64-fa3122e8affa)

The objective of the dashboard was accomplished, as it gives the user the ability to filter sales by month, year, product, location, client; and it gives an easy way to find out which month of the year the sales generated were more than the budget invested.
