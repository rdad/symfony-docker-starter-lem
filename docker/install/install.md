# On local machine

## Build php image
docker-compose build

## Start the containers
docker-compose up -d

## Open a terminal in www container
docker exec -it www_docker_symfony bash

# In the web container

## Check requirements
symfony check:requirements

## Create a new Symfony web project
symfony new project --webapp