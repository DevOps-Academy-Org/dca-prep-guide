# Enable Docker Content Trust

Enable and disable content trust per-shell or per-invocation

In a shell, you can enable content trust by setting the DOCKER_CONTENT_TRUST environment variable. Enabling per-shell is useful because you can have one shell configured for trusted operations and another terminal shell for untrusted operations. You can also add this declaration to your shell profile to have it turned on always by default.

To enable content trust in a bash shell enter the following command:

export DOCKER_CONTENT_TRUST=1

## Official Docker Documentation
[Enable and disable content trust per-shell or per-invocation](https://docs.docker.com/engine/security/trust/content_trust/#enable-and-disable-content-trust-per-shell-or-per-invocation)

