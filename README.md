# RUN

## Build from docker compose

`docker-compose up --build`

## TESTS

`docker exec -it frontend_tests_container_id sh`

`npm run test`

## RUN Production

`docker build .`
`docker run -p 8080:80 image_id`
