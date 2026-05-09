# Dockerized Node.js Application with CI/CD on AWS EC2

## Project Overview

This project is an example of the deployment of a Dockerized container Node.js web application on AWS EC2 with CI/CD pipeline using Github actions.

The application is containerized using Docker, hosted on an Ubuntu EC2 instance, and automated with Github for continous build.

## Technologies Used

* Node.js
* Express.js
* Docker
* Git & GitHub
* GitHub Actions
* AWS EC2
* Ubuntu Linux

## Features

* A Node.js application is dockerized
* CI pipeline using GitHub Actions
* The deployment of AWS EC2 
* Configured linux server
* Management of docker containers 
* Publicly accessible web application

## Docker Commands Used

### Build Docker Image

```bash
docker build -t my-node-app .
```

### Run Docker Container

```bash
docker run -d -p 3000:3000 my-node-app
```

### Check Running Containers

```bash
docker ps
```

---

##  Steps for AWS EC2 Deployment

1. Start an Ubuntu EC2 instance
2. Set Up Security Groups

   * Port 22 (SSH)
   * Port 3000 (Application)
3. Connect using SSH
4. Install Docker & Git
5. Clone GitHub repository
6. Construct Docker image
7. Run Docker container

---

##  GitHub Actions CI/CD

The project uses GitHub Actions workflow for:

* Code checkout
* Build a docker image
* Deployment workflow setup

Workflow file location:

```bash
.github/workflows/docker.yml
```

---

## Application Access

Application runs on:

```bash
http://<EC2-PUBLIC-IP>:3000
```

---

## Project Screenshots

* GitHub Repository
* GitHub Actions Workflow
* Docker Running Container
* AWS EC2 Instance
* Application Running in Browser

---

## Learning Outcome

* Docker containerization
* CI/CD pipeline basics
* AWS EC2 deployment
* Linux command-line operations
* GitHub Actions workflows
* Docker container management

## Future Enhancements

* Automated deployment to EC2
* Docker Hub integration
* Nginx reverse proxy
* HTTPS setup
* Monitoring with Prometheus & Grafana

---

## Author
Swathi P

Cloud Engineer
