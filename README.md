# docker-nodejs
Simple dockerized nodejs server

## Building your image
```
docker build . -t xsunyerb/docker-nodejs
```

### Run the image
```
docker run -p 49160:8080 -d xsunyerb/docker-nodejs
```

### Get container ID
```
docker ps
```

### Print app output
```
docker logs <container id>
```

### Open a terminal on the container
```
docker exec -it <container id> /bin/bash
```

## Test
```
curl -i localhost:49160
```
