# Spring Boot Docker Application

This repository provides a basic boilerplate for setting up a Spring Boot application with Docker, including a PostgreSQL database. It includes Docker configuration files (Dockerfile and docker-compose.yml) to containerize the application and the database, allowing for easy deployment and development.
## Prerequisites

Make sure you have Docker and Docker Compose installed on your machine.

## Running the Project

1. **Clone the repository:**
   ```sh
   git clone git@github.com:milanthapaliya/SpringBootDocker.git
2. **Navigate to the project directory:**
   ```sh
   cd SprintBootDockerApplication
3. **Run the project using docker-compose up:**
   ```sh
   docker-compose up
4. **If you make changes to your project and need to rebuild the Docker images, use docker-compose up --build:**
   ```sh
   docker-compose up --build
5. **To remove the containers, networks, and volumes created by docker-compose up, run:**
   ```sh
   docker-compose down
 