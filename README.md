# React with Docker

## Build the dev project

`docker build -f Dockerfile.dev .`

## Build the production project

`docker build .`

## Run the project

`docker-compose up`

## Test the project

`docker run -it <CONTAINER ID> npm run test`

or if container is already running 

`docker exec -it <CONTAINER ID> npm run test`