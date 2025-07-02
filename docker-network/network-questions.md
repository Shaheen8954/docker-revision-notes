# Docker Networks

## 1. What is docker network?

Docker network is crucial to communicate between to container or services in a containerised environment.Docker provides several networking options to ensure seamless communication. ex- our one container is running in isolation, one more container is also running in isolation environment, so we create a network bridge, to bring both containers into one network( call bridge network).
        

## 2. What are the default Docker networks?

Types of Docker Networks:

**Host Network**

- Uses the host machine’s network stack directly.

- Eliminates the need for port mapping.

- Limitation: Containers cannot have isolated network configurations.

**Bridge Network (default networking mode)**

- Creates an isolated network for inter-container communication.

- Requires explicit port mapping for external access.

**None Network**

- Disables networking completely.

- The container cannot communicate with other containers or the host machine.

**Bridge network ( user defined network )**

- That network is defined by the users.

  
## 3. How does Docker networking work?

## 4.Difference between bridge, host, and none networks?

## 5. How to create a custom bridge network?

`docker network create my-custom-network`


## 6. How do containers communicate with each other?

Two isolated containers communicate with each others with the help of docker network.
