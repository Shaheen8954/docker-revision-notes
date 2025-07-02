# Docker Compose
## 1. What is Docker Compose and why is it useful?

  Docker Compose is a tool that helps to manage multi-container docker application. It allows users to define and run your entire application , including services,network,and volumes,in a single docker-compose.yml file, making it easy to deploy and scale applications.

### Key Benefits of Docker Compose:

Multi-Container Management – Allows easy handling of applications consisting of multiple services.

Portability – Ensures applications run consistently across different environments (local, staging, production).

Lifecycle Management – Provides commands to start, stop, and rebuild services efficiently.

mically on a server.

Core Functionalities:

Works across different environments without modification.

Allows monitoring of running containers.

Simplifies configuration and deployment using a declarative YAML file.

How to use docker compose

Step 1: Install Docker Compose

Step 2: Create a docker-compose.yml File

Step 3: Start the application

docker-compose up -d

Step 4: Checking running containers

docker-compose ps

Step 5: Stop the application

docker-compose down

Step 6: Restart or update the application

docker-compose up -d —build

## 2. What is the default file name for a Docker Compose file?
   Docker-compose.yml

## 3. What are services in Docker Compose?

## 4. How to start, stop, and rebuild containers with Docker Compose?

In docker compose there are few commands to start, stop, and rebuild containers

docker-compose up = To start container
docker-compose down = To stop container
docker-compose up --build = To rebuild the container


## 5. How to scale services using Compose?
