# ecommerce

Introductory E-Commerce Web App built on Spring 3.2 using JavaConfig.

## Technology Stack

|  Technology           | Version           |
| --------------------- | ----------------- |
|   JDK                 | 1.7               |
|   IntelliJ Idea       | 13.0 Enterprise   |
|   Maven               | 3.0.+             |
|   Git                 | 1.8               |
|   Spring              | 3.2.5.RELEASE     |
|   Spring Security     | 3.2.0.RELEASE     |
|   Hibernate           | 4.1.0.Final       |
|   H2 SQL Embedded DB  | 1.3.160           |
|   log4j               | 1.2.16            |
|   JUnit               | 4.11              |
|   Tomcat              | 7.0.47            |
|   Thymeleaf           | 2.1.2.RELEASE     |

## Configuration

There is an ```import.sql``` in the production resources folder. It contains SQL queries to populate the database with
default values.

This includes the users:
* acme (Company user)
* johnd (Person user)

### Build Project

```
mvn clean package
```

### Build and Deploy Project into Embedded Tomcat Server

```
mvn clean
mvn tomcat7:run-war
```
### login with : 
  user : johnd
  password : password
