# Dockerfile

## 1. What is a Dockerfile?

Dockerfile is a script that contains a set of instructions to build a docker image. It automates the proccess of contenerised application by defining everything that needed to run the application, such as : 
- Base image
- Working directory
- Dependencies and libraries
- Install packages
- Environment variables
- Command to exicute when container runs

## 2. What are the common instructions used in Dockerfile?

Common Dockerfile instructions:

FROM      Base image set

WORKDIR          working directory inside the image

COPY              copy files from system to image

RUN                exicute the command during image build

EXPOSE            expose the port to inform docker which port the container is listen

ENV                sets the environment variable

ENTRYPOINT        similler to CMD, but more sticket,it cann't be overriden

CMD                exicute the command to run container


## 3. FROM, RUN, COPY, CMD, ENTRYPOINT, etc.

## 4. What is the difference between CMD and ENTRYPOINT?

`CMD` and `ENTRYPOINT` both are used in Dockerfile to define what should run inside the container, but they behave deffrently.

ENTRYPOINT is more strict then CMD

## 5. What is a multi-stage build?

A multi-stage build in docker helps to create small, optimie image, so that your image will use less storage.

## 6.  How to build an image using a Dockerfile?
