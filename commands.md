# Commands for Docker and Git

## Docker Commands

### Installation and Version
- **Update package lists**: `sudo apt-get update`
- **Install Docker**: `sudo apt-get install docker.io`
- **Check Docker version**: `docker --version`

### Managing Containers
- **List running containers**: `docker ps`
- **List all containers (including stopped)**: `docker ps -a`
- **Start a container**: `docker start <container_id>`
- **Stop a container**: `docker stop <container_id>`
- **Remove a container**: `docker rm <container_id>`
- **Inspect a container**: `docker inspect <container_id>`

### Managing Images
- **List images**: `docker images`
- **Pull an image**: `docker pull <image_name>`
- **Remove an image**: `docker rmi <image_name>`

### Running Containers
- **Run a container**: `docker run <image_name>`
- **Run a container in detached mode**: `docker run -d <image_name>`
- **Run a container with port mapping**: `docker run -d -p <host_port>:<container_port> <image_name>`
- **Execute a command in a running container**: `docker exec -it <container_id> <command>`

### Building Images
- **Build an image from a Dockerfile**: `docker build -t <image_name> .`

### Logs and Debugging
- **View logs of a container**: `docker logs <container_id>`

## Git Commands

### Cloning and Repository Management
- **Clone a repository**: `git clone <repository_url>`
- **List files in the directory**: `ls`

### Working with Files
- **Edit a file**: `vim <file_name>`

### Building and Running Applications with Docker and Git
- **Build an application image**: `docker build -t <app_name> .`
- **Run the application**: `docker run -d -p <host_port>:<container_port> <app_name>`

List Docker Images
docker images

Run a Docker Container
docker run -d --name <container-name> -e <environment-variables> -p <host-port>:<container-port> <image-name>

List Running Containers
docker ps

Stop and Remove a Container
Stop a container:
docker stop <container-id>
Remove a container:
docker rm <container-id>

Build a Docker Image
docker build -t <image-name> .

Remove a Docker Image
docker rmi <image-id>

List Docker Volumes
docker volume ls

Create a Docker Volume
docker volume create <volume-name>


