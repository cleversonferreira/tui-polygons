# Tui Polygons

##### Running the app

Run Docker command:

```bash
docker-compose up -d
```

##### Containers

API: http://localhost:3000
Mongo: http://localhost:37017
Mongo URL: `mongodb://localhost:27017/polygons`
Mongo Client: http://localhost:3300

###### Util commands

- Turn off project

```bash
docker-compose down
```

- Rebuild project

```bash
docker-compose up -d --build --remove-orphans
```

- View active containers

```bash
docker-compose ps
```

- Running commands inside docker containers

```bash
docker-compose exec {container_name} {command}
```
