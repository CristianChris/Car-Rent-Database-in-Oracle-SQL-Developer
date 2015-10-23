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

SQL_Developer project
Database creation scritpt
Input data of this database
##Scripts

## Installation

TODO: Describe the installation process

## Usage

TODO: Write usage instructions

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

TODO: Write history

## Credits

TODO: Write credits

## License

TODO: Write license
