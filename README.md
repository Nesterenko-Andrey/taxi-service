# ![](src/main/resources/images/taxi.png)<br />
The Taxi-Service application

**Project description**
----
This is a simple web application of a taxi service, in which you can try yourself as a taxi driver.<br />
<br />
**In this application you can:**<br />
- Registering and authenticating as a driver;<br />
- Delete the driver;<br />
- Create a car manufacturer, and also delete it if necessary;<br />
- Create car/delete car model;<br />
- Add a driver to one or more cars;<br />
- Display all manufacturers/cars/drivers;<br />
- Display all cars belonging to the driver you are logged in for;<br />

**Instructions for launching the project:**
----
- You need to create a database. The template can be taken from ***src\main\resources\init_db.sql***<br />
  You can use https://remotemysql.com/dashboard.php <br />
  or any other you like.
- Connect to the database in the ***taxi.util.ConnectionUtil*** class
- Install Apache Tomcat, I used version 9.0.50 <br />
  Apache Tomcat 9.0.50 you can download here https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/

**Technologies**
----
- **Java 11.0.12 2021-07-20 LTS**<br />
- **Apache Maven 3.8.1**<br />
- **Apache Tomcat 9.0.50**
- **Java Servlet API**
- **MySQL 8.0.29**
- **HTML**
- **SOLID Principles Java**
- **Dependency injection**
