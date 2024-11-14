# Data Source
AdventureWorks: A Microsoft database

## Project Overview
This project aims to

### Tools used:
- SQL Server
- Power BI - Data Visualization and report

### Useful resources
- [How to download and import AdventureWorks sample database for Microsoft SQL Server 2019][https://www.youtube.com/watch?v=FTKtNLmiIT0]: I used 2022 version but the steps are same.
- https://www.w3resource.com/sql-exercises/adventureworks: used this website for proactice questions

### SQL Queries
1. From the HumanResources.Employee table write a query in SQL to retrieve all rows and columns from the employee table in the Adventureworks database. Sort the result set in ascending order on jobtitle.
code: Select *
      From HumanResources.Employee 
      Order by jobtitle asc;
