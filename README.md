# Docker Python App

A simple Python Flask web application containerized using Docker.

## Files

- app.py — Flask web application
- Dockerfile — Docker image configuration
- requirements.txt — Python dependencies

## How to Run

Clone the repo:
git clone https://github.com/sivarajavignesh/docker-python-app.git
cd docker-python-app

Build the Docker image:
docker build -t flask-app .

Run the container:
docker run -d -p 5000:5000 flask-app

Open in browser:
http://localhost:5000

## Requirements

- Docker installed on your system


## Author

Siva Raja Vignesh
GitHub: https://github.com/sivarajavignesh
