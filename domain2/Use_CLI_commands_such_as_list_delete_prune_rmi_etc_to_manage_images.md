# Use CLI commands such as list delete prune rmi etc to manage images

Since Docker introduced an image namespace for the CLI there are different ways of triggering the same action.
For instance you can delete an image with `docker rmi` or `docker image rm`. On top of that there also command aliases for `docker image rm` like `rmi, remove`.
Currently it is not clear if it is expected to know all these variants for the certification.

## Official Docker Documentation
[docker image ls](https://docs.docker.com/engine/reference/commandline/image_ls/)  
[docker image rm](https://docs.docker.com/engine/reference/commandline/image_rm/)  
[docker image prune](https://docs.docker.com/engine/reference/commandline/image_prune/)  
