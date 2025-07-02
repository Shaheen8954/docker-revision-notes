# Docker Containers
## 1. How do you create and run a container?

`docker run -d -p 80:80 --name my-container nginx-project`

### What does this command

`docker run`  create and run the container
`-d`  run container in the background mode
`-p 8080:8080` map your host port with container port
`--name my-container` Names the container
`nginx-project`  Docker image

## 2. What is the difference between docker run and docker start?

`docker run`	Creates a new container and starts it.

`docker start`	Starts an already existing (stopped) container.

## 3. How to view running and stopped containers?

`docker ps`  view only running container

`docker ps -a`  view all running+stopped container

## 4. How to execute commands inside a container?

`docker exec -it <container name> bash`

## 5. What is the use of -d, -p, --name, and --rm flags?

`-d` = Detached mode

`-p` = Port mapping

`--name` = container name

--rm = Auto remove after stop

## 6. How to stop and remove a container?

`docker stop <container name>` = To stop container

`docker rm <container name>` = To remove container
