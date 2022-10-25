## Overview

Fullstack team manager that allows users to add, edit, delete, and search team members.

![Team Manager gif](client\src\assets\TeamBuilder.gif)

## Tech Stack
---
### Client
* Framework: Angular
* CSS library: BootStrap
### Server
* Framework: Spring Boot
* Database Connectivity: JDBC
* Database: MySQl

## Prerequisites for running locally
---

You will need the following things to properly clone and run on your computer.

* MySql
* Java 11
* Node.Js

For running the client I recommend a code editor such as [Visual Studio Code](https://code.visualstudio.com/) and for the server I recommend an IDE such as [IntelliJ](https://www.jetbrains.com/idea/).

## Database Setup

* Using your CLI you will need to create a database. 
* First you will need to login to MySQL.
```
mysql -u root
```
* Then you will need to create the database.
```
CREATE DATABASE db_name;
```
## Server Setup

To setup the back end properly you will need to navigate to this file:
```
server/src/main/resources/application.properties
```
* In the MySQL configuration implement your password and username for the spring.datatsource. 
* For the url use  
``` 
spring.datasource.url=jdbc:mysql://localhost:3306/you_db_name
```
* Lastly run the main method in your IDE.
## Client Setup

In your code editor or CLI execute the following line
```
npm run install
npm run develop
```
## Viewing in browser

* The server should be running on port 3306 and the client on port 4200
* To view in the browser go to http://localhost:4200/

## License

MIT (c) 2022 @ Steven Lofquist