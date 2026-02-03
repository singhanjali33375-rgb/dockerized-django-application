# dockerized-django-application
Dockeri# Dockerized Django Application

This project shows how to package a Django application into a Docker container for easy deployment.

## Tech Stack
- Django
- Docker

## Steps to Run

docker build -t django-docker-app .
docker run -p 8000:8000 django-docker-app

## Output
Visit http://localhost:8000zed a Django application to simplify deployment and ensure environment consistency across development and production.
Containerized a Django application using Docker to improve deployment consistency and scalability.
dockerized-django-application/
│
├── app/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── manage.py
├── requirements.txt
├── Dockerfile
├── .dockerignore
├── README.md
└── .gitignore
