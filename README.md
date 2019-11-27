# mc-forge-mods

GitHub user [itzg](https://github.com/itzg) maintains a Docker
image, [docker-minecraft-server](https://github.com/itzg/docker-minecraft-server),
that allows for one to run Minecraft on Kubernetes.

This repository hosts mods for a private server I have running inside
a Kubernetes development cluster at home. Whenever the server is restarted in k8s,
the [docker-minecraft-server](https://github.com/itzg/docker-minecraft-server) will
download the mods hosted here and run them automatically.

Pretty fun way to test out k8s deployments and potentially CI/CD pipelines in
the future.
