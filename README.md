# docker compose config for multi-domain host

## How to use

First create a network called `nginx-proxy` by running

```bash
docker network create nginx-proxy
```

Then, run

```bash
docker-compose -f nginx-docker-compose.yml up -d
```
