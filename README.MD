# Commands

_Up database_

```console
docker compose up -d db
```

_Exec Data_
_Build application_

```console
docker exec -it db psql -U postgres
```

\*\dt for see table

_Build application_

```console
docker compose build
```

_Run App_

```console
docker compose up rustapp
```

_List Containers_

```console
 docker ps -a
```

### Utils

TablePlus: for see bd
Docker Commands: `Stop all the containers
docker stop $(docker ps -a -q)
Remove all the containers

docker rm $(docker ps -a -q)`
