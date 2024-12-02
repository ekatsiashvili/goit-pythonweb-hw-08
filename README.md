# goit-pythonweb-hw-08

## intallation

```sh
git clone https://github.com/ekatsiashvili/goit-pythonweb-hw-08
cd goit-pythonweb-hw-08
```

```sh
docker-compose up --build
```

```sh
docker exec -it contacts-app alembic revision --autogenerate -m "Create contacts table"
docker exec -it contacts-app alembic upgrade head
```
