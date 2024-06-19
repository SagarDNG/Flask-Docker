# Dockerized Flask Application with Mock Service

## Stepsto run the App

This repository contains a Dockerized setup for a Flask application (`main-app`) and a mock service (`mock-service`). Follow the steps below to set up and run the application.

## Prerequisites

Ensure that Docker is installed on your machine. You can download Docker from [https://www.docker.com/get-started](https://www.docker.com/get-started).

## Step 1: Clone Repository

```
git clone https://github.com/your-username/your-repo.git
cd your-repo
```


## Step 2: Pull Docker Images

Before running the application, pull the Docker images for `main-app` and `mock-service` from Docker Hub using the following commands:

```
docker pull your-docker-username/main-app:latest
docker pull your-docker-username/mock-service:latest
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



