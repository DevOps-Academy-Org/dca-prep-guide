# Troubleshoot container and engine logs to understand a connectivity issue between containers

To troubleshoot problems with container communication, you can use ``docker network inspect`` of the different containers to see, wheter those containers are connected through the same network. Also, it is important if you're running a Docker Swarm: If so, your containers need to be bound together by an Overlay network if they're run on different nodes in the swarm. Bridge networks aren't able to communicate over node bondaries.

## Official Docker Documentation
[Network Inspect](https://docs.docker.com/engine/reference/commandline/network_inspect/)  
