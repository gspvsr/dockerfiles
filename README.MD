### Dockerfiles

Dockerfile is declarative way of creating images.

we can build the images and we can push to any docker repository.

#### How to build docker image
.....
docker build -t image-name:version .
.....

#### Filtering the lables - command
docker images --filter <label=COURSE=DevOPS>

### ENV - display the enviornment variables


docker push :
docker push <url>/<username>/<image-name>:<version>

docker push docker.io/joindevops/qi:v1

# removing all running docker continers directly.
docker rm -f `docker ps -a -q`

# removing all docker images directly.
docker rm -f `docker images -a -q`

