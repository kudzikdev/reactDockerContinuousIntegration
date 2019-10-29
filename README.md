# RUN

## Build from docker compose

`docker-compose up --build`

Browser URL: http://127.0.0.1:3000/

## TESTS

`docker exec -it frontend_tests_container_id sh`

`npm run test`

## RUN Production

`docker build .`

`docker run -p 8080:80 image_id`

Browser URL: http://127.0.0.1:8080/

## Travis 

Connect Travis to Github account

Enable repo in Dashboard

Create file in root project directory `.travis.yml`


