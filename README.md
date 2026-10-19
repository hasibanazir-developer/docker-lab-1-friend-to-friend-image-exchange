 🐳 DOCKER LAB 1
## The Friend-to-Friend Image Exchange

A hands-on Docker learning project covering containerization, image management, networking, storage troubleshooting, Docker Compose, and SSH-based image exchange.

📚 Modules Covered

### Module 1 — Introduction to Docker
- Understanding Docker and containerization.
- Learning the difference between containers and virtual machines.
- Understanding Docker images and containers.
- Exploring the Docker client and daemon.

### Module 2 — Installing Docker and Getting Started
- Checking the Docker version.
- Verifying Docker installation.
- Running the `hello-world` container.
- Understanding basic Docker commands.
- Exploring Docker system information.

### Module 3 — Working with Docker Images
- Listing available images.
- Pulling images from Docker Hub.
- Inspecting image details.
- Understanding image tags.
- Removing unused images.

### Module 4 — Creating and Running Containers
- Creating and running containers.
- Listing running and stopped containers.
- Viewing container output and logs.
- Executing commands inside containers.
- Stopping and removing containers.
- Using the `--rm` option for automatic cleanup.

### Module 5 — Building a Custom Docker Image
- Creating a Dockerfile.
- Selecting a base image.
- Defining application instructions.
- Building a custom Docker image.
- Tagging images for identification.
- Running a custom application inside a container.

### Module 6 — Sharing Images with Docker Hub
- Understanding Docker Hub repositories.
- Tagging images with a Docker Hub username.
- Authenticating with Docker Hub.
- Pushing images to a repository.
- Pulling published images onto another machine.
- Verifying the downloaded image.

### Module 7 — Debugging Containers
- Inspecting container status and exit codes.
- Checking container logs.
- Running an interactive shell inside a container.
- Inspecting files and environment variables.
- Checking available network information.
- Cleaning up stopped containers and unused resources.

### Module 8 — Docker Networking
- Listing and inspecting Docker networks.
- Creating a custom bridge network.
- Publishing container ports.
- Binding ports to localhost.
- Mapping multiple ports.
- Running containers with networking disabled.
- Removing unused networks.

### Module 9 — Docker Compose
- Creating a Dockerfile and `docker-compose.yml`.
- Validating Compose configuration.
- Building and starting multiple services.
- Running Nginx and PostgreSQL containers.
- Checking services with `docker compose ps`.
- Testing PostgreSQL database connectivity.
- Managing named volumes and networks.
- Restarting services and pulling images.
- Stopping services and removing containers.

### Module 10 — Diagnosing Storage Issues
- Checking Docker disk usage with `docker system df`.
- Inspecting detailed storage usage with `docker system df -v`.
- Checking images, containers, volumes, and build cache.
- Cleaning stopped containers with `docker container prune`.
- Cleaning unused build cache with `docker builder prune`.
- Verifying storage usage after cleanup.
- Understanding the risks of deleting Docker volumes and resources.

### Module 11 — SSH Into a Friend's Machine & Pull Their Image
- Installing and starting the OpenSSH server.
- Checking SSH server status.
- Testing a local SSH connection.
- Understanding SSH authentication and encrypted connections.
- Pulling a Docker image from Docker Hub.
- Running a container with environment variables.
- Exploring container isolation and the `--rm` option.
- Understanding the difference between a local SSH test and connecting to another machine.

## 🛠️ Technologies and Tools
- Docker
- Docker Hub
- Docker Compose
- Ubuntu on WSL 2
- Nginx
- PostgreSQL
- OpenSSH
- Git and GitHub

## 🎯 Learning Outcomes
- Understand Docker images and containers.
- Build, run, inspect, and troubleshoot containers.
- Publish and retrieve images through Docker Hub.
- Configure Docker networks and port mappings.
- Run multi-container applications using Docker Compose.
- Diagnose storage usage and safely clean Docker resources.
- Understand SSH connectivity and container isolation.
