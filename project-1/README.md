# Project 1 - Dockerized Flask Application

## Overview
This project demonstrates how to set up a basic Python Flask application using Docker. It includes a Dockerfile, Docker Compose (if needed), and configuration files.

## Requirements
- Docker
- Docker Compose (if using `docker-compose.yml`)

## Setup

### Step 1: Clone the Repository
Clone the repository to your local machine:

```bash
git clone https://github.com/lukesh-b/docker-flask-demo.git
```

### Step 2: Navigate to Project 1 Directory
```bash
cd docker-flask-demo/project-1
```

### Step 3: Build the Docker Image
Use the following command to build the Docker image:
```bash
docker build -t project-1 .
````

### Step 4: Run the Docker Container
Run the container to start the application:
```bash
docker run -p 5000:5000 project-1
```

### Step 5: Access the Application
Once the container is running, you can access the application by visiting [http://localhost:5000](http://localhost:5000).

## Configuration
You can configure the application via the `.env` file located in the `config/` directory.

## License
This project is licensed under the MIT License - see the [LICENSE](../LICENSE) file for details.

