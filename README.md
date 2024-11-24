# Next.js Docker Project

This project demonstrates how to build and run a Next.js application using Docker. It includes Dockerfile and Docker Compose configurations to streamline the development and deployment process.

## Features

- Next.js for server-rendered React applications
- Docker for containerizing the application
- Docker Compose for managing multi-container applications
- Nginx as a reverse proxy (if applicable)

## Prerequisites

- Docker installed on your local machine
- Docker Compose installed on your local machine

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/nextjs-docker-app.git
cd nextjs-docker-app 
```
### Build the Docker Image
```bash 
docker build -t my-next-app .
```
### Run the Docker Container
```bash
docker run -d -p 3000:3000 my-next-app
```