# nc-eshop-app-server

## Description
eShop-app-server is the server part of the CRM system for the sale of goods. 
The application consists of two parts:

    1) SPA for managers
    2) REST API server for client app
    
This project made to show my skills in Spring boot, Spring, Spring security, JDBC, REST, OOP, SOLID, SQL. 
In this project I used basic CRUD operations.

## Technologies
- Java 8
- Spring boot
- Spring
    - Spring security
- Oracle
- Flyway
- Lombok
- Thymeleaf
- TomCat

## How to use
- First, run the project. 
- You can then create an account to log into the app
- First created user have ADMIN role
- Admin can change role for users
- After that, you can perform CRUD operations with goods and orders

## REST API
    GET: /api/goods
    GET: /api/goods/{list}
    POST: /api/order/create 

## Setup
- Clone this project
- Prepare DB Oracle 
- Add your db configurations in application.properties (username, password, url)
````-
    spring.datasource.url=DB_URL
    spring.datasource.username=USER_NAME
    spring.datasource.password=USER_PASSWORD
````
