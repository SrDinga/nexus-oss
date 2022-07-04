# Sonatype Nexus 3 [ base-Image: debian:11.3-slim ]



## Build image
```
docker build  -t nexus3 .
```


## Running
```
docker run -d -p 8081:8081 --name nexus nexus3
```
