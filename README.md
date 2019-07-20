
# Setting

Clone this repo

add an `.env` file at the root

```
CLUSTER_NAME=bifrost
USER_NAME=dav
USER_PASSWORD=def@ultP@ssw0rd
```


# Basic commands

start the stack
```
docker-compose up -d --build
```

stop it

```
docker-compose down
```

See logs 

```
docker-compose logs -t -f
```

access hdfs through the name node
```
sudo docker exec -it namenode bash
```

# Tools: 

- [hue](http://localhost:8000)

# Sources

[main repos](https://hub.docker.com/r/bde2020)

[base of the docker-compose](https://github.com/big-data-europe/docker-hadoop/blob/master/docker-compose.yml)

parts added
[hue](https://hub.docker.com/r/bde2020/hdfs-filebrowser)