## Docker images

Various docker images:

* lichee

### Manual build

```sh
git clone https://github.com/StefanMavrodiev/docker-images
cd docker-images
cd <name>
docker build . -t olimex/<name>
```

### Pushing to dockerhub

```sh
docker login
docker push olimex/<name>
```
