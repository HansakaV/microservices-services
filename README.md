# Backend: Services

This repository contains the business logic microservices for the Bus Depot Management System.

## Student Information
- **Name:** Mahesh Hansaka
- **Student Number:** 2301691104
- **GCP Project ID:** bus-depot-management-491905 

## Microservices
1. **Labour Service**: Handles employee management (MySQL).
2. **Bus Service**: Manages the bus fleet (MongoDB + Google Cloud Storage).
3. **Booking Service**: Manages passenger bookings (MySQL).

## Technology Stack
- Java 
- Spring Boot
- Spring Data JPA / MongoDB
- Google Cloud Storage SDK

## Setup Instructions
1. Ensure MySQL and MongoDB are running.
2. Update `application.yaml` or Config Server with your database credentials and GCS Bucket ID.
3. Build with `./mvnw clean install`.
4. Run using `java -jar target/[service-name]-0.0.1-SNAPSHOT.jar`.
