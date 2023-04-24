# Spring Boot Quiz Application

This is a quiz application built with Spring Boot, Hibernate, JDBC, and JSP.

## Getting Started

### Prerequisites

- JDK 8 or higher
- Maven
- MySQL

### Installing

1. Clone the repository:
   ```
   git clone git@github.com:d104601/quizApplication.git
   ```
2. Create a MySQL database:
    ```
    create database quizapp
    ```

3. Add or Modify the `src/main/resources/application.properties` file to match your MySQL configuration:
    ```
    database.hibernate.url=jdbc:mysql://localhost:3306/quizapp
    database.hibernate.driver=com.mysql.cj.jdbc.Driver
    database.hibernate.username={your username}
    database.hibernate.password={your password}
    database.hibernate.dialect=org.hibernate.dialect.MySQL5Dialect
    database.hibernate.showsql=true
    database.hibernate.hbm2ddl.auto=update
    
    spring.mvc.view.prefix=/WEB-INF/jsp/
    spring.mvc.view.suffix=.jsp
    ```
4. Run your project using your IDE(IntelliJ recommended) or Maven:
5. Open your browser and visit http://localhost:8080


## Tech Stacks Used
- Spring Boot
- Spring MVC
- Hibernate
- JSP
- MySQL
- Maven
- Tomcat
- Bootstrap