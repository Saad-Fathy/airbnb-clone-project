# Airbnb Clone Project 

## Overview
The Airbnb Clone Project is a real-world learning project designed to simulate the development of a scalable booking platform inspired by Airbnb.  
The project focuses on **backend systems, database design, API development, and application security**, while also exposing learners to collaborative workflows and modern DevOps practices.

## Learning Objective
- Master collaborative team workflows using GitHub.
- Deepen their understanding of backend architecture and database design principles.
- Implement advanced security measures for API development.
- Gain proficiency in designing and managing CI/CD pipelines for efficient deployment.
- Strengthen their ability to document and plan complex software projects effectively.
- Develop an understanding of integrating technologies like Django, MySQL, and GraphQL in a unified ecosystem.

## Team Roles
- **Business Analyst (BA)**: Bridges customer needs with technical implementation.

- **Product Owner (PO)**: Defines the product vision and ensures alignment with customer needs (often more business-focused than the BA).

- **Project Manager (PM)**: Oversees timelines, budgets, and team motivation.

- **UI/UX Designer**: Crafts user journeys and interface designs driven by usability and engagement.

- **Software Architect**: Shapes the technical architecture and sets coding standards.

- **Developers**: Front-end, back-end, or full-stack engineers who implement features.

- **QA Engineer**: Ensures functionality, performance, and security meet requirements.

- **Test Automation Engineer**: Builds automated testing systems to enhance quality and speed.

- **DevOps Engineer**: Manages CI/CD and streamlines delivery between development and operations.

## Technology Stack
- **Django**: A high-level Python web framework used for building the RESTful API.
- **Django REST Framework**: Provides tools for creating and managing RESTful APIs.
- **PostgreSQL**: A powerful relational database used for data storage.
- **GraphQL**: Allows for flexible and efficient querying of data.
- **Celery**: For handling asynchronous tasks such as sending notifications or processing payments.
- **Redis**: Used for caching and session management.
- **Docker**: Containerization tool for consistent development and deployment environments.
- **CI/CD Pipelines**: Automated pipelines for testing and deploying code changes.

## Database Design

1. **Users**
   - `id`
   - `name`
   - `email` (unique)
   - `password`
   - `role` (e.g., guest, host, admin)

2. **Properties**
   - `title`
   - `description`
   - `location`
   - `price_per_night`

3. **Bookings**
   - `check_in_date`
   - `check_out_date`
   - `status` (e.g., pending, confirmed, cancelled)

4. **Reviews**
   - `rating` (1–5)
   - `comment`

5. **Payments**
   - `amount`
   - `payment_method`
   - `payment_status` (e.g., paid, pending, failed)