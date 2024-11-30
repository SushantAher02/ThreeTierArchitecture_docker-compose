# ThreeTierArchitecture_docker-compose
# Three-Tier Architecture with Docker Compose

This repository demonstrates a simple three-tier architecture using Docker Compose. The architecture includes the following tiers:

1. **Frontend**: A web server (e.g., Nginx or Apache) serving static files or acting as a reverse proxy.
2. **Backend**: An application server (e.g., PHP, Python, Node.js) handling business logic.
3. **Database**: A database server (e.g., MySQL, PostgreSQL) for data storage.

## Prerequisites

Ensure you have the following installed on your system:

- Docker: [Installation Guide](https://docs.docker.com/get-docker/)
- Docker Compose: [Installation Guide](https://docs.docker.com/compose/install/)

## Repository Structure

Here's a README.md that matches the provided folder structure:

markdown
Copy code
# Three-Tier Architecture with Docker Compose

This repository implements a three-tier architecture using Docker Compose, structured as follows:

1. **Web Tier**: Serves as the frontend using Nginx to serve static content (e.g., HTML).
2. **App Tier**: A backend powered by PHP to handle dynamic requests.
3. **Database Tier**: A MySQL database for data persistence.

## Folder Structure

The repository is organized as follows:

. ├── web/ # Web (Frontend) tier │ ├── myhtmlcode/ # Contains static HTML files │ │ └── index.html # Entry point for the frontend │ ├── Dockerfile # Dockerfile for the web service │ └── default.conf # Nginx configuration for the web server ├── app/ # Application (Backend) tier │ ├── myphpcode/ # Contains PHP files │ │ └── index.php # Entry point for the backend │ └── Dockerfile # Dockerfile for the app service ├── db/ # Database tier │ ├── Dockerfile # Dockerfile for the database service │ ├── init.sh # Script for initializing the database │ └── init.sql # SQL file for database schema and seed data ├── docker-compose.yml # Compose file to orchestrate all services └── README.md # Documentation
  

