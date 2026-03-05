# DOCKER-CLI-COMMANDS
This repo contains basic commands that are needed in DOCKER

## Build Image
```bash
docker build -t nameofimage .
```
## See all images in Docker
```bash
docker images
```

## Running Docker Image (container creation)
```bash
docker run -it -d -p localport:containerport ImageName
```
## To See containers
```bash
docker ps
```
## To connect with DOCKER HUB
```bash
docker login
```

## To create a tag of Local image
```bash
docker tag socials accountName/image name
```
## To push image on Docker Hub
```bash
docker push taggedImagename
```
