# Taxi-service
![taxi_fly.jpg](taxi_fly.jpg)

## Project description: :pushpin:
Taxi Service is a simple web application that simulates the work of a taxi service.
The project is implemented in Java with SOLID principles & Dependency Injection, has a 3-tier architecture.

## Project has next features: :pushpin:
- Display All Drivers
- Display All Cars
- Display All Current Cars
- Display All Manufacturers
- Create new Car
- Create new Manufacturer
- Add Driver to Car

## Structure: 3-tier architecture: :pushpin:
- **DAO** - Data Tier
- **Service** - Business Tier
- **Controllers** - Presentation Tier

## Database diagram: :pushpin:
![diagram.jpg](diagram.jpg)

## Technologies: :pushpin:
- Java v.11;
- Apache Tomcat v.9;
- MySQL v.8;
- Maven v.3.8;
- Java Servlet v.4;
- JSTL v.1.2;
- In project used pattern of Dependency Injector.

## Instructions for run project: :rocket:
- Configure TomСat.
- Copy, paste and run the script from this file `src/main/resources/init_db.sql` into MySQL.
- In order to connect to the database it is necessary to add current data in the following fields `URL, USERNAME, PASSWORD, JDBC_DRIVER` in this file `src/main/java/taxi/util/ConnectionUtil.java`.
- Add configurations in TomCat Server.
- Start the project.
- Also you can test the APP using the browser of your PC. Click on the link: :point_right: [**link**](https://service-taxi-nba.herokuapp.com)
