<p align="center">
<img src="./src/main/resources/pic1.png">
</p>
<h1 align="center">Taxi-Service</h1>

___
## Navigation
* [Description](#Description)
* [Functionality](#Functionality)
* [Project Structure](#Project-Structure)
* [Used Technologies](#Used-Technologies)
* [Project run instructions](#Project-run-instructions)
___
## Description
```
Uncomplicated web-application designed for work with
Taxi-Service functional, such as registration,
authentication, creating, reading, updating, deleting.
```
___
## Functionality
* registration users(drivers);
* authentication user(driver);
* creating/reading/updating/deleting drivers
* creating/reading/updating/deleting manufacturers
* creating/reading/updating/deleting cars
___
## Project Structure 
Project consist of three layers:
1. DAO - Data access layer
2. Services - Business layer
3. Controllers - UI layer
___
## Used Technologies
1. Java Database Connectivity API (JDBC)
2. Java Servlet
3. JavaServer Pages (JSP)
4. JSP Standard Tag Library (JSTL)
___
## Project run instructions
To run this project we need these programs(or alternatives):
* MySQL
* Tomcat
* IntelliJ IDEA Ultimate

1. Firstly, clone project from GitHub to new project.
2. Secondly, we should create DB in MySQL by using
SQL queries from `/src/main/resources/init_db.sql`.
3. Then configuring connection by adding URL, Driver,
Username, Password in `\src\main\java\taxi\util\ConnectionUtil`
4. Finally, we should add Tomcat configuration in
IntelliJ IDEA and set deployment.

>Now we can run project by using IntelliJ IDEA Ultimate.
___