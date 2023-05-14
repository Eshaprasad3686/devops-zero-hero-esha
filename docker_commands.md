Docker Images

List all available Docker images on your system
```sh
docker images

```



Download a Docker image from a registry
```sh
docker pull <image_name>

```



Push an image to a registry

```sh
 docker push <image_name>

```
 


Remove a Docker image from your system

```sh
 docker rmi <image_name>

```



Build a Docker image from a Dockerfile

```sh
 docker build -t <image_name> <path_to_Dockerfile>

```



Build an image from a Dockerfile located in the current directory

```sh
 docker build .

```



Create an image from a Dockerfile and tag it

```sh
 docker build -t [name]:[tag] [dockerfile-path]

```


Create an image from a container

```sh
 docker commit [container] [new-image]

```



Tag an image

```sh
 docker tag [image] [image]:[tag]

```



Show history for an image

```sh
docker history [image]

```



Save an image to a tar archive file

```sh
docker save [image] > [tar-file]

```



Remove unused images

```sh
docker image prune

```



Docker Containers


Create and start a new container from a Docker image

```sh
 docker run <image_name>

```



List all running containers

```sh
 docker ps

```



Stop a running container

```sh
 docker stop <container_id>

```



Start a stopped container

```sh
 docker start <container_id>

```



Restart a running container

```sh
 docker restart <container_id>

```



Pause process in a running container

```sh
 docker pause <container_id>

```



Unpause the process in a running container

```sh
 docker unpause <container_id>

```



Remove a stopped container from your system

```sh
 docker rm <container_id>

```



Send a KILL signal to stop a container

```sh
 docker kill <container_id>

```



Execute a command inside a running container

```sh
docker exec -it <container_id> <command>

```



View the logs of a container

```sh
docker logs <container_id>

```



Run a container and remove it after it stops

```sh
docker run -rm <image>

```



Run an interactive process

```sh
docker run -it <image>

```



Docker Container Management


Create a container (without starting it)

```sh
 docker create [image]

```



Create an interactive container with pseudo-TTY

```sh
 docker create -it [image]

```



Rename an existing container

```sh
 docker rename [container] [new-name]

```



Forcefully remove a container, even if it is running

```sh
 docker rm -f [container]

```



Retrieve logs created before a specific point in time

```sh
 docker logs -f --until=[interval] [container]

```



Update the configuration of one or more containers

```sh
 docker update [container]

```



View port mapping for a container

```sh
 docker port [container]

```



Show running processes in a container

```sh
 docker top [container]

```



View live resource usage statistics for a container

```sh
 docker stats [container]

```



Show changes to files or directories on the filesystem

```sh
docker diff [container]

```



Copy a local file to a directory in a container

```sh
docker cp [file-path] CONTAINER:[path]

```



Docker Compose


Start containers defined in a Docker Compose file

```sh
 docker-compose up

```



Stop and remove containers defined in a Docker Compose file

```sh
 docker-compose down

```



Build or rebuild services defined in a Docker Compose file

```sh
 docker-compose build

```



View the logs of a specific service defined in a Docker Compose file

```sh
 docker-compose logs <service_name>

```



Docker Networks


List all available Docker networks

```sh
 docker network ls

```



Create a new Docker network

```sh
 docker network create <network_name>

```
 
 

Inspect details about a Docker network

```sh
 docker network inspect <network_name>

```



Remove a Docker network

```sh
 docker network rm <network_name>

```



Docker Volumes

List all available Docker volumes


```sh
 docker volume ls

```



Create a new Docker volume

```sh
 docker volume create <volume_name>

```



Inspect details about a Docker volume

```sh
 docker volume inspect <volume_name>

```



Remove a Docker volume

```sh
 docker volume rm <volume_name>

```



General Management


Log in to a Docker registry

```sh
 docker login

```



Log out of a Docker registry

```sh
 docker logout

```



List low-level information on Docker objects

```sh
 docker inspect [object]

```



Show the version of the local Docker installation

```sh
 docker version

```



Display information about the system

```sh
 docker info

```



Remove unused images, containers, and networks
```sh
 docker system prune

```
