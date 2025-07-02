# Docker Images

## 1. What is docker image?
Docker image is a tamplate or blueprint that has everything which is needed  to run docker container like- code, libraries, dependencies, required tools.

## 2. How to list all Docker images?

`docker images`   To see all images

## 3. How to pull an image from Docker Hub?

`docker pull <image-name>`

## 4. How are Docker images layered?

A dockerfile is made up of layers, every layer is like a step of your Dockerfile.

## 5. What is the difference between docker pull and docker build?

We use Docker pull to download image from docker registery,whereas
we use Docker build to build image from Dockerfile.

## 6. How to delete a Docker image?

`docker rmi <image-name>`

## 7. What does docker image prune do?

 `docker image prune` It removes unused all docker images from your system to free up space.
