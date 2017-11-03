# Understand and describe the types of traffic that flow between the Docker engine registry and UCP controllers

The traffic between DTR and UCP is always encrypted to ensure security. Traffic between containers is not encrypted by default. DTR / UCP management traffic used Mutual TLS 

## Official Docker Documentation
[Docker UCP Security](https://success.docker.com/Architecture/Docker_Reference_Architecture%3A_Securing_Docker_EE_and_Security_Best_Practices#ucpsecurity)  
[Docker Swarm Networking](https://docs.docker.com/engine/swarm/networking/)  

## Third Party Resources
[Which firewall ports are used in Docker Swarm?](https://www.bretfisher.com/docker-swarm-firewall-ports/)  
