A simple professional portfolio website deployed using Docker and Nginx.

## Project Overview

This project demonstrates how to containerize a static website using Docker.

The website is packaged into a custom Docker image and deployed using Docker Compose.

## Architecture


User Browser
|
|
Port 8080
|
|
Nginx Docker Container
|
|
HTML Website


## Technologies Used

- HTML
- CSS
- Docker
- Dockerfile
- Docker Compose
- Nginx
- Git & GitHub

## Project Structure


docker-website-project/

├── website/
│ └── index.html
│
├── Dockerfile
│
├── compose.yaml
│
├── README.md
│
└── .gitignore


## Docker Concepts Implemented

- Created custom Docker image using Dockerfile
- Used Nginx as a base image
- Used Docker Compose for container management
- Used port mapping to access the application
- Used volume mounting for live website updates

## How to Run

Clone the repository:


git clone <repository-url>


Go into the project:


cd docker-website-project


Start the application:


docker compose up --build


Open in browser:


http://localhost:8080


## Stop Application


docker compose down


## Author

Kantheti Sai Vishnu

DevOps | Cloud | Linux | Docker