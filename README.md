# School Sample Database

This repository contains the schema and data for the School database. The sample School database is used in various places throughout the Entity Framework documentation.

[see](https://docs.microsoft.com/en-us/ef/ef6/resources/school-database)

Here are the steps to create the database:

* Open Visual Studio
* ```View -> Server Explorer```
* Right click on ```Data Connections -> Add Connection...```
* If you haven’t connected to a database from Server Explorer before you’ll need to select **Microsoft SQL Server** as the data source
* Connect to either **LocalDB** or **SQL Express** depending on which one you have installed
* Enter **School** as the database name
* Select **OK** and you will be asked if you want to create a new database, select Yes
* The new database will now appear in Server Explorer
* Right-click on the database in Server Explorer and select **New Query**
* Copy the following [SQL](./school.sql) into the new query, then right-click on the query and select **Execute**
