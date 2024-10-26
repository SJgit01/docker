1. Docker Installation and Setup

    ./pkg_install.sh <package_name>
    which docker
    docker --version

2. Docker Service Management

    docker ps
    systemctl status docker
    sudo usermod -aG docker <username> && newgrp docker

3. Docker Image Management

    docker images
    docker pull <image_name>:<tag>

4. Docker Container Operations

    docker run -d <image_name>:<tag>
    docker run -dit <image_name>:<tag>
    docker run -d -e <env_variable>=<value> <image_name>:<tag>
    docker ps -a
    docker exec -it <container_id> bash
    docker run -d -p <host_port>:<container_port> <image_name>:<tag>
    docker run -d --name <container_name> <image_name>:<tag>

5. Git Operations

    git clone <repository_url>
    cd <directory_name>/

6. Docker Build Commands

    docker build -t <image_name> .

7. Running Built Containers

    docker run -dit <image_name>
    docker run -p <host_port>:<container_port> <image_name>:<tag>

8. Stopping and Removing Containers

    docker kill <container_id>
    docker rm <container_id>
    docker stop <container_id>

9. Docker System Management

    docker system prune
    docker volume ls
    docker rmi <image_id>
    docker images | grep <search_term>

10. Docker Authentication

    docker login
    docker logout

11. Running MySQL Container with Custom Settings

    docker run -d --name <container_name> -e MYSQL_ROOT_PASSWORD=<password> <image_name>:<tag>
    docker exec -it <container_id> bash
