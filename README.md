# Taxi-service
![taxi_fly.jpg](taxi_fly.jpg)

# Project description:
Taxi Service is a simple web application that simulates the work of a taxi service.
The project is implemented in Java with SOLID principles & Dependency Injection, has a 3-tier architecture.

## Project has next features:
- Display All Drivers
- Display All Cars
- Display All Current Cars
- Display All Manufacturers
- Create new Car
- Create new Manufacturer
- Add Driver to Car
- Delete Driver from Car

## Structure: 3-tier architecture:
- **DAO** - Data Tier
- **Service** - Business Tier
- **Controllers** - Presentation Tier

## Database diagram:
![diagram.jpg](diagram.jpg)

## Technologies:
- Java v.11;
- Apache Tomcat v.9;
- MySQL v.8;
- Maven v.3.8;
- Java Servlet v.4;
- JSTL v.1.2;
- In project used pattern of Dependency Injector.

## Instructions for run project:
:white_check_mark: Configure TomСat.
:white_check_mark: Copy, paste and run the script from this file `src/main/resources/init_db.sql` into MySQL.
:white_check_mark: In order to connect to the database it is necessary to add current data in the following fields `URL, USERNAME, PASSWORD, JDBC_DRIVER` in this file `src/main/java/taxi/util/ConnectionUtil.java`.
:white_check_mark: Add configurations in TomCat Server.
:white_check_mark:- Start the project.
:white_check_mark: Also you can test the APP using the browser of your PC. Click on the link: :point_right: [**link**](https://service-taxi-nba.herokuapp.com)
