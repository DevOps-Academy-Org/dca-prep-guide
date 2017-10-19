# Create a Docker bridge network for a developer to use for their containers

By default, Docker Engine connects container via a default bridge to the network of the node.
However, only overlay networks in a Swarm context let containers communicate further than the nodes network boundaries.
In special cases, own bridge networks can be added to i.e. allow for communication only between two special containers.

## Official Docker Documentation
[How to connect two containers via a private bridge](https://docs.docker.com/engine/userguide/networking/work-with-networks/#basic-container-networking-example)

[The extended description of Network Create](https://docs.docker.com/engine/reference/commandline/network_create/#extended-description)

[One can also change the default bridge of the Docker Engine](https://docs.docker.com/engine/userguide/networking/default_network/build-bridges/)
