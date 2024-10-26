# 1. Docker Installation and Setup
```bash
1. ./pkg_install.sh <package_name>
2. which docker
3. docker --version
```

# 2. Docker Service Management
```bash
1. docker ps
2. systemctl status docker
3. sudo usermod -aG docker <username> && newgrp docker
```

# 3. Docker Image Management
```bash
1. docker images
2. docker pull <image_name>:<tag>
3. docker pull <image_name>:<tag>
4. docker pull <image_name>:<tag>
5. docker pull <image_name>:<tag>
```

# 4. Docker Container Operations
```bash
1. docker run -d <image_name>:<tag>
2. docker run -dot <image_name>:<tag>
3. docker run -dit <image_name>:<tag>
4. docker run <image_name>:<tag>
5. docker run -d -e <env_variable>=<value> <image_name>:<tag>
6. docker ps -a
7. docker exec -it <container_id> bash
8. docker run -d <image_name>:<tag>
9. docker run -d -p <host_port>:<container_port> <image_name>:<tag>
10. docker run -d --name <container_name> <image_name>:<tag>
```

# 5. Git Operations
```bash
1. git clone <repository_url>
2. cd <directory_name>/
```

# 6. Docker Build Commands
```bash
1. docker build -t <image_name> .
2. docker build -t <image_name> .
3. docker build -t <image_name> .
4. docker build -t <image_name> .
```

# 7. Running Built Containers
```bash
1. docker run -dit <image_name>
2. docker run -dit <image_name>:<tag>
3. docker run <image_name>:<tag>
4. docker run -p <host_port>:<container_port> <image_name>:<tag>
5. docker run -d -p <host_port>:<container_port> <image_name>
```

# 8. Stopping and Removing Containers
```bash
1. docker kill <container_id>
2. docker rm <container_id>
3. docker kill <container_id> && docker rm <container_id>
4. docker rm -i <container_id>
5. docker rm -i <container_id>
6. docker stop <container_id>
7. docker rm <container_id>
```

# 9. Docker System Management
```bash
1. docker system prune
2. docker volume ls
3. docker rmi <image_id>
4. docker rmi <image_id>
5. docker images | grep <search_term>
```

# 10. Docker Authentication
```bash
1. docker login
2. docker logout
```

# 11. Running MySQL Container with Custom Settings
```bash
1. docker run -d --name <container_name> -e MYSQL_ROOT_PASSWORD=<password> <image_name>:<tag>
2. docker exec -it <container_id> bash
```

