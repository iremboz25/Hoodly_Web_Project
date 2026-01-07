# Hoodly_Web_Project
Hoodly is a full-stack web application developed as a functional prototype for a specialized online clothing store.he primary objective of this project is to demonstrate the practical integration of a modern Frontend (React) with a structured Backend (Spring Boot) and a PostgreSQL database to simulate a real-world shopping experience.

Core Technologies
Frontend
React.js: Component-based architecture for a maintainable codebase.
Material UI (MUI): Professional grid system and pre-built UI components.
React Context API: Global state management for persistent Cart and Wishlist data.
React Router: For fluid, client-side navigation.

Backend
Spring Boot (Java): High-performance backbone handling HTTP requests and business logic.
Spring Data JPA / Hibernate: Simplified database interactions and ORM mapping.
RESTful API: Clean API design serving data in JSON format.

Database
PostgreSQL: Relational database for robust storage of product metadata and categories.
Data Seeding: Supports initialization via SQL scripts and CSV imports for immediate deployment.

Installation & Setup
Prerequisites
Java SDK (Version 17 or higher)
Node.js (LTS version)
PostgreSQL

1. Database Setup
Create a database named hoodly.
Configure your credentials in backend/src/main/resources/application.properties.
2. Backend Setup
   cd backend
./mvnw spring-boot:run
3. Frontend Setup
   cd frontend
npm install
npm start
