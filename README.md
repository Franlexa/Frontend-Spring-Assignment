# Frontend-Spring-Assignment
# Web Programming 2024 - Sensor Management Application

# Introduction
This project is part of the Web Programming course taught by Guillaume EHRET in 2024. The application manages sensors, rooms, and windows using Java, Spring Boot, and Spring Data. It exposes a REST API documented with Swagger for managing sensors and windows.
# Features
Entities:  Sensors
Rooms 
Windows
REST API: Exposed endpoints for managing sensors and windows.
Swagger UI: Documentation for the API is available through Swagger.
H2 Database: In-memory database for data storage.
# Technologies Used
Java
Spring Boot
Spring Data
Spring Web
Swagger UI
H2 Database

# Setup and Installation
Clone the Repository:
bash
git clone https://github.com/Franlexa/Frontend spring Assignmemt.git
cd your-repository
Run the Application:

    Make sure you have Java and Maven installed.
    Use the following command to run the application:

bash
mvn spring-boot:run
Access the API:
    Open your web browser and navigate to:
    http://localhost:8080/swagger-ui.html
    This will take you to the Swagger UI where you can interact with the API.
API Endpoints
    GET /sensors: Retrieve a list of sensors.
    POST /sensors: Create a new sensor.
    GET /windows: Retrieve a list of windows.
    POST /windows: Create a new window.
    (Add additional endpoints as necessary)

Contributing

This project is an individual assignment. However, feedback is welcome.
License

This project is licensed under the MIT License.
