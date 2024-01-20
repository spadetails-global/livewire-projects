## To bring all containers up:

* docker-compose up -d

#### Command will take a while to run, since it will build the images for the first time.

#### note: any change you make to the Dockerfile or any other file that the Dockerfile uses (excluding docker-compose.yaml) you will need to build the images again for the changes to take effect by executing the following command.

* docker-compose build && docker-compose up -d

## To list all running containers:

* docker ps

## To run specific commands in your app container:

* docker-compose exec blog_app bash

## To access your Laravel Application visit:

* localhost:8000

## To exit a container:

* exit

## To bring all containers down:

* docker-compose down

