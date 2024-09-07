# CricketScoreBackend

## Description

**CricketScoreBackend** is a Spring Boot application designed to provide endpoints for accessing cricket match information. It leverages the power of Spring Boot's REST framework, JDBC for database interaction, and uses the jsoup library for fetching live scores from external websites.

## Features

- Fetch live cricket matches
- Retrieve all matches
- Get the point table

## Technologies Used

- **Spring Boot**: Framework for building RESTful APIs
- **Spring Data JPA**: ORM tool for data persistence
- **Spring Boot Starter Web**: For building web applications and RESTful services
- **jsoup**: HTML parser for scraping live cricket scores from external websites
- **MySQL**: Database for storing cricket match data
- **POSTMAN**: For testing the application

## Endpoints

### 1. Get Live Matches

- **Endpoint**: `/match/live`
- **Method**: `GET`
- **Description**: Retrieves a list of live cricket matches.
- **Response**: A JSON array of live match objects.


### 3. Get Point Table

- **Endpoint**: `/match/point-table`
- **Method**: `GET`
- **Description**: Retrieves the point table.
- **Response**: A JSON array of arrays, where each inner array represents a row in the point table.
