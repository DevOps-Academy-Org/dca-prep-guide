# Identify which IP and port a container is externally accessible on

Basically, you can look up every port which is exposed by using ``docker inspect CONTAINER`` on every container. However, to just get the port binding information, you could use ``docker port CONTAINER``. To make this more useable, you can also script this like ``docker port `docker ps -q` `` to get the export of all bound ports of all running containers. The official way would be to use just ``docker ps``.

## Official Docker Documentation
[Docker Engine Port Command](https://docs.docker.com/engine/reference/commandline/port/#show-all-mapped-ports)  
