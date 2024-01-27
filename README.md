# DevOps

### Starting the dev environment

###### Build the project
```shell
docker-compose -p brand-fashion build
```

###### Run containers
```shell
docker-compose -p brand-fashion up -d
```

###### Apply migrations
````bash
docker-compose -p highlights exec -T server npm run migrate:up
````

###### Stop containers
```shell
docker-compose -p highlights stop [container_name]
```

###### Stop and remove
```shell
docker-compose -p highlights down [container_name]s
```
