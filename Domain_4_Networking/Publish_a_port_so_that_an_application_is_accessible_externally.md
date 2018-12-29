# Publish a port so that an application is accessible externally

There are multiple ways to publish a port of an application. Basically, you can use ````EXPOSE```` during the ````docker build```` process and then, on using ````docker run```` use the parameter ``-P`` to publish all exposed ports of said Image to the external IP of the node. You are also free to expose said ports manually via ``-p``, i.e. ``-p="8080:80"`` to expose the port 80 of the container to the port 8080 of the host. Without giving an external port, like ``-p="80"`` you'll export the port 80 of the container to an random port. You can also lock the port export to a specified interface of the host, i.e. with ``-p="192.168.2.6:8080:80"``. It is also possible to randomize the external port in that scenario: ``-p="192.168.2.6::80"``. 

## Official Docker Documentation
[Docker Documentation on EXPOSE](https://docs.docker.com/engine/reference/run/#expose-incoming-ports)  
[Publish port in swarm mode](https://docs.docker.com/v17.09/engine/swarm/services/#publish-a-services-ports-directly-on-the-swarm-node)
[Publish service ports externally to the swarm](https://docs.docker.com/engine/reference/commandline/service_create/#publish-service-ports-externally-to-the-swarm--p---publish)
