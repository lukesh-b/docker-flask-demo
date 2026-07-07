# Project 1 Setup Guide

## Prerequisites
- Docker installed
- Repository cloned

## Running the application

1. Navigate to the project directory:
   ```bash
   cd docker-flask-demo/project-1
   ```
2. Build the image:
   ```bash
   docker build -t project-1 .
   ```
3. Run the container:
   ```bash
   docker run -p 5000:5000 project-1
   ```
4. Open the app:
   Visit http://localhost:5000 and you should see "Hello, Docker World!".

## Configuration
Copy the example env file and adjust as needed:
```bash
cp config/.env.example config/.env
```
`.env` is gitignored, so local settings are never committed.

## Stopping
```bash
docker ps          # find the container id
docker stop <id>
```
