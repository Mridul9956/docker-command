vim docker_command.md   # create or edit file
git add docker_command.md
git commit -m "Added docker commands list"
docker images                  # List all images
docker rmi <image_id>          # Remove an image
docker build -t myapp:1.0 .    # Build image from Dockerfile
docker tag myapp:1.0 myuser/myapp:1.0   # Tag image
docker ps                      # List running containers
docker ps -a                   # List all containers (running + stopped)
docker run <image>             # Run a container from image
docker run -it <image> bash    # Run container in interactive mode
docker start <container_id>    # Start a stopped container
docker stop <container_id>     # Stop a running container
docker restart <container_id>  # Restart container
docker rm <container_id>       # Remove container
docker logs <container_id>     # Show container logs
docker exec -it <container_id> bash   # Access container shell
docker --version               # Show Docker version
docker info                    # Display system-wide information
docker login                   # Login to Docker Hub
docker logout                  # Logout from Docker Hub
docker search <image>          # Search image on Docker Hub
docker pull <image>            # Pull image from Docker Hub
docker push <image>            # Push image to Docker Hub

