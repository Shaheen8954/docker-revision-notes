# Docker Volumes
## 1. What is a volume in Docker?

Docker volume is a storage mechanism used to persist data generated by the containers, even after they are stopped or deleted.unlike bind mounts, volumes are managed by docker and are stored data in a specific directory /var/lib/docker on the host machine. 

## 2. How are volumes different from bind mounts?

Docker manages data safely in the hidden folder.

Create and use:

`docker volume create my-volume`

`docker run -v my-volume:/app/data nginx`

 Useful when you want to edit files on your machine and see changes live in the container.

 `docker run -v /home/shaheen/my-app:/app nginx`

## 3. How to create, list, and remove volumes?

`docker volume create my-volume`  To create volume

`docker volume ls`  To list volume

`docker volume rm my-volume`  Remove volume

`docker volume prune`  remove all unused volume


## 4. How to share volumes between containers?

Use the same name volume to share volume between containers.

Step 1. Create a volume:

`docker volume create shared-data`

Step 2. Start the first container using the volume:

`docker run -d --name container1 -v shared-data:/app/data busybox sleep 3600`

Step 3. Start the second container using the same volume:

`docker run -d --name container2 -v shared-data:/app/data busybox sleep 3600`



## 5. What is the default volume path?

Docker stores volumes in this path on your host system:

`/var/lib/docker/volumes/`

