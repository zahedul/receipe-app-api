# Recipe App Api

Its a Django learning app.

### specs

- Django
- REST Api
- Docker
- PostgreSql
- Unittest

## Docker command

Build docker
```shell script
docker-compose build
```

Run Django unittest
```shell script
docker-compose run --rm app sh -c "python manage.py test && flake8"
```

Remove all container
```shell script
docker system prune
```
