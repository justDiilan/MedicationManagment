# MedicationManagment

This program system is designed to control medication retention. 

The server also communicates with IoT devices (temperature and humidity sensors) to monitor storage conditions. In case of storage conditions violation, the server will handle the error. 

Separately, a simulation of the IoT device has been developed which reads the temperature and humidity values around. In case of violations, it gives an audible signal and also sends the data to the server in the database.

The project was developed in C# language.
The framework ASP. NET Core. RESTful API and MVC pattern are used. JWT Token authorization.
IoT device C++.
MSSQL Server database.
There is also a second version of the system that uses PostgreSQL.
