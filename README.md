# Fullstack Docker Application

This is a fullstack web application built using React for the frontend, Express for the backend, and PostgreSQL as the database. The project will be containerized using Docker in the upcoming stages.

## Setup I - Initial Project Structure

This phase focuses on setting up the basic structure of the project before adding Docker and database services.

### Completed in this step:

- Created folders for frontend, backend, and database
- Added empty Dockerfiles for frontend and backend
- Created `.env` file and `docker-compose.yml` (empty)
- Implemented basic Express backend with PostgreSQL connection
- Built a simple React frontend that fetches data from the backend

## Setup II - Dockerizing the Application

This phase focuses on containerizing the frontend, backend, and database services, and running them using Docker Compose.

**Completed in this step:**

- Wrote Dockerfile for the backend (Node + Express)  
- Wrote Dockerfile for the frontend (React)  
- Configured `docker-compose.yml` with services: frontend, backend, and db  
- Created `.env` file with database configuration  
- Ran the full-stack app using `docker-compose up`  
- Verified app works in browser (frontend → backend → database)