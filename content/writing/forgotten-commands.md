+++
title = "Commands I Use and Forget"
date = 2021-10-07

[taxonomies]
tags = ["Linux"]

[extra]
abstract = "A simple list of commands."
date_fmt = "Last Updated: Oct 7, 2021"
platforms = ["GitHub"]
platform_links = ["https://github.com/yuzonightly/personal-site-posts"]
+++

## Docker

```bash
docker pull <image>
```

List images.

```bash
docker images
```

```bash
docker image rm <image>
```

Specify port number for _host_ and _container_.

```bash
docker run -d -p<host>:<container> <image>
```

```bash
docker run -d --name <name> <image>
```

```bash
docker stop <container>
```

```bash
docker start <container>
```

List all containers.

```bash
docker ps -a
```

Show logs for the specified container.

```bash
docker logs <container>
```

```bash
docker logs <container> -f
```

```bash
docker exec -it <container> /bin/bash
```

```bash
docker network ls
```

```bash
docker network create <network>
```

## Hardhat

```bash
npx hardhat compile
```

```bash
npx hardhat node
```

```bash
npx hardhat run scripts/deploy.js --network localhost
```

## GitHub

```bash
git reset --soft HEAD~1
```

```bash
git merge origin/main
```

```bash
git pull
```

## sea-plus

```bash

```

```bash

```
