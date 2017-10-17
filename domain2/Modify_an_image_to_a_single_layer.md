# Modify an image to a single layer

## Official Docker Documentation

### Without rebuilding
- create a container from the image: [docker create](https://docs.docker.com/engine/reference/commandline/create/)
- export the container to a flattened tar: [docker container export](https://docs.docker.com/engine/reference/commandline/export/)  
- load the image back: [docker image import](https://docs.docker.com/engine/reference/commandline/image_import/)  

### With rebuilding
See the `--squash` option of [docker build](https://docs.docker.com/engine/reference/commandline/build/#options)  

## Third party resources
[Flatten a Docker container or image](https://tuhrig.de/flatten-a-docker-container-or-image/)

