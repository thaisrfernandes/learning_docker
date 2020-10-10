# Learning Docker
Learning how to create a docker image using docker/docker-compose and upload it to docker hub.

- **master branch:** learning basic docker.

- **docker-compose branch:** learning docker compose using application with nodemon.

Tutorial: https://www.youtube.com/watch?v=AVNADGzXrrQ

## Docker Commands


**Running image:**
```
docker build -t [name your image] [dockerfile path]
```

**Running image:**
```
docker-compose up
```

**See your images (w/ repository, tag, id and creation date):**
```
docker images
```

**Login into dockerhub:**
```
docker login -u [username]
```

**Sending your image to dockerhub:**
```
docker tag [image tag] [username]/[image name]
```

```
docker push [username]/[image name]
```


