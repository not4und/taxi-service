# taxi-service
## Project description
A simple web-application for taxi service that supports authentication, registration and other CRUD operations.
## Project structure
* Data access layer - DAO
* Application layer - service
* Presentation layer - controller
## Features
* Registration
* Login
* Logout
* Display All Drivers
* Display current driver's Cars
* Display All Cars
* Display All Manufacturers
* Create new Driver
* Create new Car
* Create new Manufacturer
* Add Driver to Car
## Tech stack
* JDBC
* Servlet
* JSP
* JSTL
* HTML, CSS
* Apache Tomcat
* MySQL
## How to start the app
1. Install Apache Tomcat 9.0.65, MySQL, MySQL Workbench.
2. Initialize the databases from resources/init_db.sql in MySQL Workbench.
3. Change connection info in taxi.util.ConnectionUtil:
    ```java
    private static final String URL = "YOUR DATABASE URL";
    private static final String USERNAME = "YOUR USERNAME";
    private static final String PASSWORD = "YOUR PASSWORD";
    ```
4. Run the app.
