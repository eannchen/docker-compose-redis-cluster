## Create local redis cluster

```bash
$ ip=$(ipconfig getifaddr en0) docker-compose up -d --build
$ docker-compose run redis-cli

$ docker-compose down
```