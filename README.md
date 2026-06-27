# Static-website-using-docker-
Built and containerized a static website using Docker and Nginx. Created a Docker image with a custom Dockerfile, deployed the application in a container, and managed it using Docker CLI.


# Docker Static Website

## Overview
This project demonstrates how to containerize a simple static website using Docker and Nginx. The website consists of HTML and CSS files and is served from an Nginx web server running inside a Docker container.

## Technologies Used
- Docker
- Nginx
- HTML
- CSS

## Project Structure
```
Static-website-using-docker/
├── index.html
├── style.css
├── Dockerfile
└── README.md
```

## Prerequisites
- Docker installed on your system

## Build the Docker Image
```bash
docker build -t Static-website-using-docker .
```

## Run the Container
```bash
docker run -d -p 8080:80 --name mysite Static-website-using-docker
```

## Access the Website
Open your browser and visit:

```
http://localhost:8080
```

## Docker Commands
View running containers:
```bash
docker ps
```

Stop the container:
```bash
docker stop mysite
```

Start the container:
```bash
docker start mysite
```

Remove the container:
```bash
docker rm mysite
```

## Features
- Containerized static website
- Lightweight Nginx web server
- Easy deployment using Docker
- Beginner-friendly DevOps project

## Learning Outcomes
- Creating a Docker image
- Writing a Dockerfile
- Running and managing Docker containers
- Serving a static website with Nginx
