# Increase number of replicas

Running Services on a Docker Swarm can be scaled in different ways: `docker service scale SERVICE=NUMBER`. This works only for replicated services. Another way is using `docker service update --replicas=NUMBER SERVICE` to achieve the same goal. Additionally, multiple services can be scaled at once, using the `docker service scale SERVICE1=NUMBER1 SERVICE2=NUMBER2 [...]` syntax.

## Official Docker Documentation
[Service Scale](https://docs.docker.com/engine/reference/commandline/service_scale/#examples)
