# ⚡ DevOps Command Center

A professional multi-container DevOps portfolio project built using Docker, Docker Compose, Nginx, Alpine Linux, and Ubuntu.

## Project Overview

This project demonstrates how to build and deploy a custom website using Docker Compose with multiple services.

## Technologies Used

- Docker
- Docker Compose
- Nginx
- Alpine Linux
- Ubuntu Linux
- HTML
- CSS

## Project Features

- Custom responsive DevOps dashboard
- Multi-container application
- Custom Docker image
- Docker Compose orchestration
- Container-to-container communication
- Nginx health checks
- Automatic container restart policy

## Architecture

- Web Service: Custom Nginx website
- Client Service: Alpine Linux container
- Network: Default Docker Compose network

## Run the Project

Build and start containers:

```bash
sudo docker compose up -d --build

```

Check container status:

```bash
sudo docker compose ps
```

Test container communication:

```bash
sudo docker compose exec client wget -qO- http://web
```

View logs:

```bash
sudo docker compose logs
```

Stop and remove containers:

```bash
sudo docker compose down
```

## Access Website

Open in your browser:

http://localhost:8087

## Learning Outcomes

- Understanding Docker Compose
- Managing multiple containers
- Building custom Docker images
- Configuring health checks
- Understanding Docker networking
- Deploying containerized applications

## Author

DevOps Learning Portfolio — Day 18
