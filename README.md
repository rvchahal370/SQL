# SQL
In the SQLBasicFirst- Firtsly Created the table and inserted the values into it then performed the Aggregative functions(SUM(), COUNT(), MIN(), MAX(), AVG()) on that along with Distinct

In the SQLBasicSecond- where clause used with Like and IN aong with Group by and Order By

In the CASEANDHaving- case statement and Having clause is with the aggregate functions
Note - where clause is not recommended along with the aggregative function whereas Having clause is used with the aggregative functions

In the SQLBasicUnion- Full Outer Join, Inner Join, Right Join and Left Join are used

In the BasicUnion- Union and UnioAll are used
Note- Union is used to combine the data from two table which are having the same number of columns and of same data types,
whereas joins can combine the data from two differenet tables but it will be done with help of one common column like Employee Id, Union don't require comumn column
joins adds another column but union adds another rows

In the UpdateDeleteAndBasic- update and delete queries are executed along with the Alias and Partition By
Note- Alias can be used with or without 'AS', it can be used to rename the column, table
    - Partition by can used along with aggregative functions where there is no need of Group By
    
In the CTEAndTempTable- CTE and TempTable are used
Note- CTE is used like Temp Table but unlike Temp tables the records are Temporary and not stored in the memory 
    - Temp table always starts with #
    
In the BasicFunctions- Used the function like TRIM, LTRIM, RTRIM, REPLACE, SUBSTRING, UPPER, LOWER

In the StoreProcedure- Created, Execute and Drop the Store Procedure
Note- Store Procedure is a set of multiple SQL statements that can be executed and stored in the database
    - Store Procedure can be use with the different input values entered by multiple users 
    - Store procedure is used to increase the performance and to decrease the traffic on the network 
    - Once the store procedure is updated at one place then automatically it will be updated for another places/users 
    
In the SubQuery- Written the SubQuery with the Column, From and Where Clause
Note- SubQuery is a query within the mail query
    - It can be slow as compare to CTE and Temporary tables
    
In the PortfolioProject- Created the project based on the Coronavirus data collection from the ourworldindata website.
Firstly data was downloaded from the website in CSV Excel format and transferred it into two different excel sheets, 1st is CovidDeaths and 2nd is CovidVaccinations,
Thereafter imported the excel through 'SQL Server 2022 Import Export data' while choosing the source and destination address.
Then calculated the total count and total percentage of death, population continent or world vide for each day. At last, Implemented the different queries on the viccanation data
Difference between nvarchar and varchar? - varchar is stored as regular 8 bit data (1 byte per character) but nvarchar stores data at 2 byte per character,
Due to that nvarchar can hold upto 4000 characters and takes double the space as SQL Varchar. 

In the DataCleaningProject- Converted the date format and Null values in the address field with the appropriate address corresponding to the common parcelID
Splitted the Address field into different Address, City and state columns with the help of SUBSTRING, CHARINDEX, PARSENAME and REPLACE functions
Converted Y and N into 'Yes' and 'No' in the SoldAsVacant column with the help of CASE statement
Removed the duplicate rows with the help of CTE, ROWNUMBER() and PARTITION BY
Deleted the duplicate columns with the help of ALTER and DROP
Renamed the column name with the help of SP_RENAME
