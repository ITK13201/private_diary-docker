# private_diary-docker

I ported https://github.com/ITK13201/private_diary to docker.

## Usage

```bash
$ docker-compose up -d
$ docker exec private_diary-docker_web_1 python manage.py migrate
```

## How to show logs

```bash
docker-compose logs
```
