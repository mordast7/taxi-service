# Taxi Service
### Overview
This is a simple and minimalistic taxi application

---

#### Functionality
- driver authentication
- creating manufacturers, cars and drivers
- displaying manufacturers, cars and drivers
- deleting manufacturers, cars and drivers
- assigning drivers to cars
- displaying available cars for currently authorized user

---

### Inner structure

---

#### Project are based 3-layer architecture, implemented following SOLID principles:

- Data access layer: DAO
- Business logic layer: Services
- Presentation layer: Controllers

---

#### Necessary technologies:
- Java 11
- JDBC
- MySQL
- HttpServlets, HttpFilters
- HTML, CSS, JSP, JSTL
- Apache Tomcat (v9.0.50)
- Maven

---

### How to run project

#### Tools needed:

- IntelliJ IDEA Ultimate
- ApacheTomcat
- MySQL

1. Clone the project on your IDE
2. Create DB using script from resources/init_db_my.sql
3. Change connection properties in src/main/java/taxi/util/ConnectionUtil
4. Configure Tomcat local server
5. Enjoy the project!

---