# Docker Basics
## 1. What is Docker and why is it used ?
  Docker is a tool that allowes you to build and run application in lightweight portable containers, those application will run on any system, those cotainers includes everything which needed to run container such as code, libraries, dependencies. but they share the host system’s operating systems kernel. 

## 2. Difference between Docker and virtual machines?
  Docker is just package your application with required dependencies, it doesn't take much space, it runs on the host's opreting system.

  Vertual machine is like running a whole new computer inside your real computer, with it's own opreting system, seperate from your own machine.
  
  It is fully isolated,  like a complete computer in software.
  
  ex- you have windows machine and you want linux too,
     Instead of purchaging new computer you create a vertual machine on your windows laptop.
     You install linux inside it and now you are using linux inside windows.
     

## 3. What are the main components of Docker?

  Docker has some main components that help docker to do everything like - building an image, running container,and so on. There are main components-

  Docker Engine - It is a core service that runs everything, it's like a docker brain, it has - 
  - Docker deamon(dockerd)
  - Docker cli
  - Rest API

  Docker Image

  Docker Container

  Dockerfile
  

## 4. What is Docker Engine?

  Docker Engine is the core component of Docker that allows you to build, run and manage containers. It is lightweight runtime and containerization platform that enable application to run in isolated environments.

### Components of Docker Engine:

- Docker Daemon – Runs in the background and manages containers, images, network, and volumes.

- API Server – Allows developers and other tools to communicate with Docker Deamon programmatically.

- Docker CLI (docker commands) - A command-line tool to interact with Docker Daemon.

### Types of Docker Engine

- Docker Engine - Community (CE): Free and open-source version for developers.

- Docker Engine - Enterprise (EE): Paid version with additional security and support for entrprises.



## 5. What is a Docker image and container?

  Docker image is a tamplate or blueprint of your application, it contains your app, code, libraries, dependencies, all the software it needs, instructions to run your app.

  Container is an isolated environment which directly talk to kernel and create separate environment with Dockerfile. When you share it with your client it will create separate environment. Container are very lightweight and it can be share easily.

### Some important keys -

- Lightweight - docker containers are lightweight

- Fast startup - they run fast your application

- Portable - containers allows to run application in all environments.

- Scalable - it can increase scalability of application according to the requirement.



