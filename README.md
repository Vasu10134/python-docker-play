# Dockerising Python

This repository demonstrates how to Dockerize a simple Python application. By using Docker, we can encapsulate the Python app in a container for easy deployment and scalability. The project includes the necessary setup to build, run, and manage the Python application inside a Docker container.

## What we did
- **Dockerized Python application**: We created a Docker container that runs a Python application using the `python:3.9-slim` base image.
- **Dockerfile setup**: A custom Dockerfile was created to install dependencies, copy files, and run the Python script.
- **.dockerignore file**: Excluded unnecessary files from being copied into the Docker image to optimize the build.

## Steps to Run

1. **Build the Docker image**:
    ```bash
    docker build -t python-docker-app .
    ```

2. **Run the Docker container**:
    ```bash
    docker run python-docker-app
    ```

## Project Structure

- **Dockerfile**: Defines the steps to build the Docker image.
- **app.py**: Python application that is run inside the container.
- **.dockerignore**: Specifies files that should not be copied into the Docker image.

## Why Dockerize?
Docker provides an isolated environment for running your Python applications, making it easier to manage dependencies and ensuring that the application runs consistently across different systems. It also simplifies deployment and scaling in production environments.
---

Feel free to explore, modify, or enhance this project as needed!
