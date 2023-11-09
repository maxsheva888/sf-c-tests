## Build containers

```bash
docker-compose -f ./docker/docker-compose.yml build
```


## Run containers

```bash
docker-compose -f ./docker/docker-compose.yml up -d
```


## App bash

```bash
docker-compose -f ./docker/docker-compose.yml exec -u www-data php-fpm bash
```
