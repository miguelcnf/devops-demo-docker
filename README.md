# Docker demo

#### Demo

1. Install docker: https://www.docker.com/get-started
2. Build docker image: `docker build -t hello:latest .`
4. Run docker image: `docker run -p 8080:8080 --name hello-world -d hello:latest`
5. Check the container state: `docker ps`
6. Access it with: `curl 0:8080/`
7. Cleanup with: `docker rm -f hello-world`

