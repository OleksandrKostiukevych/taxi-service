# Taxi service
## Description
Taxi service application enables to use database of taxi drivers and cars with simple web interface.<br>
Application is scalable and easy to maintain due to programming principles, applied inside.<br>

This web application is based on JDBC and servlets, supports user authentication and has basic<br> CRUD operations.
The project meets SOLID principles. Functionality allows you to work with a <br>database of drivers and cars.
It contains the following functions:
- Registration
- Authentication
- Adding cars, drivers, manufacturers to database
- Adding relations between drivers and cars
- Deleting cars, manufacturers, drivers
## Structure
| Module     |                  Description                  |
|------------|:---------------------------------------------:|
| controller |    servlets for car, driver, manufacturer     |
| dao        |                database logic                 |
| exception  |               custom exception                |
| lib        |           injector and annotations            |
| model      |      models of car, driver, manufacturer      |
| service    | CRUD operations for car, driver, manufacturer |
| util       |            connection to database             |
| web filter |             authentication filter             |
| resources  |                  init.db.sql                  |
| webapp     |   jsp-pages and web.xml configuration file    |
## Used technologies, patterns and principles
- JDBC, servlets, Dependency Injection, OOP, three-tier architecture;
- Tomcat, JDK 18, Maven, MySQL 8;
- HTML, CSS, JSP, JSTL, and SQL.
## How to run the application?
- Install JDK, any IDE, Tomcat v.9.0.7, MySQL;
- Fork this project
- Open project in IDE
- Run SQL script from resources folder in MySQL Workbench, IDE<br> or console to create a schema and tables.
- Configure Tomcat
- Run program.
