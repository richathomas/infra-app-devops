## DevOpsify the go web application

The main goal of this project is to implement DevOps practices in the Go web application. The project is a simple website written in Golang. It uses the net/http package to serve HTTP requests.

## DevOps practices include the following:

Creating Dockerfile (Multi-stage build)
Containerization
Continuous Integration (CI)
Continuous Deployment (CD)


## Summary Diagram

<img width="2048" height="748" alt="img5" src="https://github.com/user-attachments/assets/5d47eede-a4c1-411d-8108-003d8b72443c" />

## Creating Dockerfile (Multi-stage build)

The Dockerfile is used to build a Docker image. The Docker image contains the Go web application and its dependencies. The Docker image is then used to create a Docker container.

We will use a Multi-stage build to create the Docker image. The Multi-stage build is a feature of Docker that allows you to use multiple build stages in a single Dockerfile. This will reduce the size of the final Docker image and also secure the image by removing unnecessary files and packages.

## Containerization

Containerization is the process of packaging an application and its dependencies into a container. The container is then run on a container platform such as Docker. Containerization allows you to run the application in a consistent environment, regardless of the underlying infrastructure.

We will use Docker to containerize the Go web application. Docker is a container platform that allows you to build, ship, and run containers.

Commands to build the Docker container:

```bash
docker build -t <your-docker-username>/go-web-app .


Command to run the Docker container:

