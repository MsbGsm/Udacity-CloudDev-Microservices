# Udacity-CloudDev-Microservices

This project is the 3rd from Udacity Cloud Developer Nanodegree, it helped me to get used with Docker and Containers, Kubernetes, CI/CD using travis-CI

Each folder in the main is considered as a Microservice:
  - Feed Service - Backend
  - User Service - Backend
  - Frontend - ionic
  - Reverse proxy - Nginx - Backend
  
  
  To build Docker images you need to have Docker and docker-compose installed and run the following command:
    `docker-compose -f udacity-c3-deployment/docker/docker-compose-build build --parallel`
    
  And to run the application, you need to set your own cloud credentials as long as your RDS credential too in the aws-secret.yaml and env-secret respectivly
  then you run the following command while in the "udacity-c3-deployment/docker/" directory:
  
  `docker-compose up`
