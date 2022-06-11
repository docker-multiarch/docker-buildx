# ⚠️ DEPRECATED ⚠️

The Buildx plugin is now available in the official Docker image since `20.10.16`, see
https://github.com/docker-library/docker/pull/361.

# Docker with Buildx

![Docker](https://github.com/docker-multiarch/docker-buildx/actions/workflows/docker.yaml/badge.svg)

[![Docker GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/moby/moby?label=Docker&logo=Docker)](https://github.com/moby/moby)
[![Buildx GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/docker/buildx?label=Buildx)](https://github.com/docker/buildx)

This repository adds [Docker Buildx](https://github.com/docker/buildx) into the
official **latest** [Docker image](https://github.com/docker-library/docker).

The following files are reused from the
[official Docker image reposiory](https://github.com/docker-library/docker):

- `Dockerfile`: Modified to add the [Buildx plugin](https://github.com/docker/buildx).
- `docker-entrypoint.sh`: Unmodified
- `modprobe.sh`: Unmodified
