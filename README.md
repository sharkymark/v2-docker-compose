---
name: Docker Compose configs
description: Docker Compose configs for Coder v2
tags: [cloud, docker]
---

# v2-docker-compose

Docker Compose is one method to deploy Coder's control plane.

## Mac option

Because the Docker group is not available on macOS, you can add a Proxy container to the `docker-compose.yaml` to let the `$HOME` user that starts Coder's control plane create containers in Docker Desktop

## Linux option

The default `docker-compose.yaml` that is in [the Coder v2 OSS repo.](https://github.com/coder/coder/blob/main/docker-compose.yaml)
