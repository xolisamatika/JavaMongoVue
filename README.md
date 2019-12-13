# Assessment

## Pull submodules
```
git submodule init && git submodule update
```
## Build the backend app jar
```
cd credicard-restapi &&  ./gradlew build && cd -
```

### build the docker images and containers and the start them 
```
docker-compose up -d --build
```
