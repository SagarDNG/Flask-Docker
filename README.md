# Dockerized Flask Application with Mock Service

## Steps to run the App

This repository contains a Dockerized setup for a Flask application (`main-app`) and a mock service (`mock-service`). Follow the steps below to set up and run the application.

## Prerequisites

Ensure that Docker is installed on your machine. You can download Docker from [https://www.docker.com/get-started](https://www.docker.com/get-started).

## Step 1: Clone Repository

```
git clone https://github.com/SagarDNG/Flask-Docker.git
cd Flask-Docker
```


## Step 2: Pull Docker Images
(This step is optinal, as docker-compose will pull if we didn't do it manually)
Before running the application, pull the Docker images for `main-app` and `mock-service` from Docker Hub using the following commands:

```
docker pull sagardng/main-app:latest
docker pull sagardng/mock-service:latest
```

## Step 3: Start Docker Compose
Run Docker Compose to start the services defined in the docker-compose.yml file:

```
docker-compose up
```

## Step 4: Access the Application:

Main App: Navigate to [http://localhost:5000](http://localhost:5000) to access the Flask application.
Mock Service: Navigate to [http://localhost:5001/mock_endpoint](http://localhost:5001/mock_endpoint) to access the mock service endpoint.

## Step 5: Stopping the Application:
To stop the running Docker containers, press Ctrl + C in the terminal where docker-compose up is running.



