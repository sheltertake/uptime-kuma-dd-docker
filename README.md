# uptime-kuma-dd-docker

```shell
git clone https://github.com/sheltertake/uptime-kuma-dd-docker.git .

```

## configuration

 - open .env and customize with your values

```txt
DD_API_KEY=YOUR_DD_API_KEY
DD_SITE=YOUR_DD_SITE
```

## build

```shell
docker-compose build
```

## run

```shell
docker-compose up
```

## configure uptime kuma

 - http://localhost:3001/
 - username/password
 - insert some monitor
 - check traces in dd
