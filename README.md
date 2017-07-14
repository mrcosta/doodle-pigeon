# doodle-pigeon

```bash
docker build -t="mrcosta/doodle-pigeon" .
```

to run is necessary first to build the application using the build image
and then build the image to run the application.

```bash
docker run -p8080:8080 --rm -it mrcosta/doodle-pigeon
```

docker-compose run test ./gradlew test