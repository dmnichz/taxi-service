# Taxi Service
### A simple webapp with CRUD operations
- driver authentication or creating a new driver
- creating manufacturer, car, driver
- assigning drivers to cars
- displaying all manufacturers, cars, or drivers
- displaying all cars for currently authorized driver
- deleting manufacturers, cars and drivers

#### You can test webapp [here](https://immense-ocean-21118.herokuapp.com/login)

---
### This application has a three-tier architecture:

- Data access layer (DAO)
- Application layer (service)
- Presentation layer (controllers)
---
### Technologies:
- Java 11
- Apache Tomcat (v9.0.50)
- MySQL
- JDBC
- Servlet
- JSP
- JSTL
- HTML, CSS
- Maven
---
### Run Project

#### Tools to run project:

- IntelliJ IDEA Ultimate IDEA
- ApacheTomcat
- MySQL

1. Clone this repository to your IDE
2. Create DB in MySQL Workbench using script from resources/init_db.sql
3. In src/main/java/taxi/util/ConnectionUtil change connection properties
4. Configure TomCat Local server
   (Add New Configuration -> TomCat -> Local -> Fix -> taxi-service:war exploded -> OK)
5. Run TomCat Local server
