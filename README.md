cat > README.md << 'EOF'
# Docker Task - AWS EC2

## What I did
Installed and explored Docker on AWS EC2 (Ubuntu t2.micro)

## Tech Stack
- AWS EC2
- Docker

## Commands Explored

### Images
- `docker pull <image>` - Download an image
- `docker images` - List all images
- `docker inspect <image>` - View image details

### Containers
- `docker run <image>` - Create and start a container
- `docker ps` - List running containers
- `docker ps -a` - List all containers
- `docker exec -it <container> bash` - Enter a container
- `docker stop <container>` - Stop a container
- `docker rm <container>` - Remove a container

### Volumes
- `docker volume create <name>` - Create a volume
- `docker volume ls` - List volumes
- `docker volume inspect <name>` - Inspect a volume

### Networks
- `docker network ls` - List networks
- `docker network create <name>` - Create a network
- `docker network inspect <name>` - Inspect a network

## Screenshots
See /screenshots folder for terminal output proofs.
EOF
