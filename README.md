# ![](images/taxi.png)<br />
# The Taxi-Service application

**Project description**
----
This is a simple web application of a taxi service, in which you can try yourself as a taxi driver.<br />
<br />
**In this application you can:**<br />
- Register, log in/out as a driver;<br />
- Create and delete cars/manufacturers/drivers;<br />
- Add a driver to one or more cars;<br />
- Display all manufacturers/cars/drivers;<br />
- Display all cars belonging to the driver you are logged in for;<br />

**Instructions for launching the project:**
----
- You need to create a database in your DBMS. The template can be taken from ***src\main\resources\init_db.sql***<br />
  You can use https://remotemysql.com/dashboard.php <br />
  or any other you like.
- Edit ***taxi.util.ConnectionUtil*** class - set needed parameters in following fields
``` java
    private static final String URL = "Set URL to database";
    private static final String USERNAME = "Set USERNAME";
    private static final String PASSWORD = "Set PASSWORD";
    private static final String JDBC_DRIVER = "Set path to the JDBC_Driver";
```
- Install Apache Tomcat, I used version 9.0.50 <br />
  Apache Tomcat 9.0.50 you can download here https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/
- Configure the Tomcat server in your IDEA and Run the project.<br />

**Technologies**
----
- Java 11<br />
- Apache Maven 3.8.1<br />
- Apache Tomcat 9.0.50
- Java Servlet API
- MySQL 8.0.29
- JSP
