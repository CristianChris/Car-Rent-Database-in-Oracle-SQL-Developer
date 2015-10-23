# Rent a car Database in Oracle SQL Developer

## Database description
There is a rent car company which provides car renting. The car renting is possible only with customer_ID, driving_ID and personal data.

Each car is identified by vehicle_ID. It has it's brand, model, category and availability status, all this four attributes are mandatory. Car category represents the class, type of the car (convertible, sedan, etc...). We store also information about vehicle current km, vehicle engine size and the price for each vehicle separatly depending on it's mileage .

Each booking procedure requires from the customer to select from the option pickup and return date, vehicle category, additional adding some gadgets to the car (GPS, child seat and satellite radio), adding our type of insurance (full covering and partial covering), fill in personal data(name, surname, e-mail, etc...).

After the car was returned, possible repair_fee or fuel_fee may appear if the car was damaged or the tank fuel is not full, all this information is stored in booking procedure.

##Data model
![alt tag](https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/img/Data%20model.png "Data model")

There are no loops in data model.
##Relational model
![alt tag](https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/img/Relational%20model.png "Relational model")


##[SQL Statements + Relational Algebra(click on me)](https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/SQL_querys/SQL_Statements%2BRelational_Algebra.pdf)

##[SQL Statements Cover(click on me)](https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/SQL_querys/SQL_Statements_Cover.pdf)

##Scripts
[SQL project](https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/data/Car_Rent_Model_Oracle_SQL_Developer_Project.zip)

[Database creation scritpt](https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/data/database_creation_script.sql)

[Data for testing queries random generated](https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/data/Data_for_testing_queries_random_generated.sql)

## Instructions
In order to do some changes in this particular database you need to have [Oracle SQL developer](http://www.oracle.com/technetwork/developer-tools/sql-developer/overview/index-097090.html) installed. After you need to download the [SQL project](https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/data/Car_Rent_Model_Oracle_SQL_Developer_Project.zip). Once Oracle SQL developer is installed you can open this project and to the changes you want.

If you want to use this structure of database you just have to run the [Database creation scritpt](https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/data/database_creation_script.sql) in your SQL Worksheet. This script will generate the tables.

To insert information into the tables you can use either manual method or again SQL Worksheet. I have generated some random [data](https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/data/Data_for_testing_queries_random_generated.sql) for each tables that you can use to test the queries that you want to implement.

Here is a script(https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/data/erase%20script.txt) that you may use to delete all the information from your database including the data from table and tables in general. To run this script just paste it in the SQL Worksheet.

##References
[Report](https://github.com/CristianChris/Car-Rent-Database-in-Oracle-SQL-Developer/blob/master/Report_rent_a_car_DB.pdf)

[Sample of the DB project] (https://users.fit.cvut.cz/~valenta/bie-dbs/sem-project/index.html)

