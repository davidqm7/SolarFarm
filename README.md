# Solar Farm Management System

## Overview
The Solar Farm Management System is a Java-based application that helps administrators manage and track solar panels across different sections of a solar farm. The system provides CRUD (Create, Read, Update, Delete) operations for solar panel management and maintains data persistence using CSV file storage.


## Features
- Add new solar panels to the farm
- Update existing panel information
- Remove panels from the system
- Display all panels in a specific section
- Data validation for panel properties
- Persistent data storage using CSV
- Spring dependency injection support

## Technical Requirements
- Java 21 (or Java 17 with Spring 5.3.27)
- Maven
- Spring Framework
- JUnit 5 for testing

## Architecture
- Three-layer architecture (UI, Domain, Data)
- Dependency injection using Spring
- Repository pattern for data access
- MVC pattern in UI layer

## Error Handling
- Custom DataException for data layer errors
- Validation results using PanelResult class
- User-friendly error messages in UI
  
