# PHP Docker Images Builder

An easy way to create and maintain PHP Docker images

[![Latest Stable Version](https://poser.pugx.org/token27/docker-images-php/v/stable.svg)](https://packagist.org/packages/token27/docker-images-php)
[![License](https://poser.pugx.org/token27/docker-images-php/license)](https://packagist.org/packages/token27/docker-images-php)
[![Total Downloads](https://poser.pugx.org/token27/docker-images-php/d/total)](https://packagist.org/packages/token27/docker-images-php)

## Requirements

The following prerequisites are needed for ```PHP Docker Images Builder``` to run.

- Docker
    - [Linux](https://docs.docker.com/)
    - [Windows](https://docs.docker.com/desktop/windows/install/)


- Makefile
    - [Linux](https://www.gnu.org/software/make)
    - [Windows](http://gnuwin32.sourceforge.net/packages/make.htm)

## How to start ?

### Set up your Docker Hub Credentials:

```
export CONTAINER_REGISTRY_USERNAME=[YOUR_USERNAME]
export CONTAINER_REGISTRY_PASSWORD=[YOUR_PASSWORD]

make ci-docker-login
```

### Build, test or push PHP `CLI` and `FPM` images:

```
make build
make test
make push
```

### Build, test or push ONLY PHP `CLI` images:

```
make build-cli
make test-cli
make push-cli
```

### Build, test or push ONLY PHP `FPM` images:

```
make build-fpm
make test-fpm
make push-fpm
```

- PHP 8.0
    - [CLI](https://hub.docker.com/repository/docker/token27/php)  token27/php:cli-8.0
    - [CLI DEV](https://hub.docker.com/repository/docker/token27/php)  token27/php:cli-8.0-dev
    - [FPM](https://hub.docker.com/repository/docker/token27/php)  token27/php:fpm-8.0
    - [FPM DEV](https://hub.docker.com/repository/docker/token27/php)  token27/php:fpm-8.0-dev


- PHP 7.3
    - [CLI](https://hub.docker.com/repository/docker/token27/php)  token27/php:cli-7.3
    - [CLI DEV](https://hub.docker.com/repository/docker/token27/php)  token27/php:cli-7.3-dev
    - [FPM](https://hub.docker.com/repository/docker/token27/php)  token27/php:fpm-7.3
    - [FPM DEV](https://hub.docker.com/repository/docker/token27/php)  token27/php:fpm-7.3-dev


- PHP 7.2
    - [CLI](https://hub.docker.com/repository/docker/token27/php)  token27/php:cli-7.2
    - [CLI DEV](https://hub.docker.com/repository/docker/token27/php)  token27/php:cli-7.2-dev
    - [FPM](https://hub.docker.com/repository/docker/token27/php)  token27/php:fpm-7.2
    - [FPM DEV](https://hub.docker.com/repository/docker/token27/php)  token27/php:fpm-7.2-dev


- PHP 7.1
    - [CLI](https://hub.docker.com/repository/docker/token27/php)  token27/php:cli-7.1
    - [CLI DEV](https://hub.docker.com/repository/docker/token27/php)  token27/php:cli-7.1-dev
    - [FPM](https://hub.docker.com/repository/docker/token27/php)  token27/php:fpm-7.1
    - [FPM DEV](https://hub.docker.com/repository/docker/token27/php)  token27/php:fpm-7.1-dev

## Docs

See [Documentation](docs).