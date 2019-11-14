# Laravel PHP Container

[![pipeline status](https://gitlab.com/lorenzocalamandrei/simple-laravel-docker/badges/master/pipeline.svg)](https://gitlab.com/lorenzocalamandrei/simple-laravel-docker/commits/master)

This repo is also mirrored on GitHub.
But GitHub is used only to deploy on DockerHub, using automated build.

- [GitHub Repo - Laravel Container](https://github.com/CalamandreiLorenzo/simple-laravel-docker)
- [GitLab Repo - Laravel Container](https://gitlab.com/lorenzocalamandrei/simple-laravel-docker)
- [Docker Hub - Laravel Container](https://hub.docker.com/r/lorenzocalamandrei/laravel-php)

## Requirements

- Docker

## How to run

Run this container whit the following command: 

```bash
docker container run --rm -ti -p 8000:8000 -v $(pwd):./ --user local lorenzocalamandrei/laravel-php bash
```

After that you can use composer to initialize it or use the pre-installed laravel cli with `laravel new project` for example.
Otherwise you can proceed as you prefer.

## Contributors

- Lorenzo Calamandrei <nexcal.dev@gmail.com>
