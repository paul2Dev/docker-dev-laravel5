# Docker dev environment for laravel 5

## Setup

copy files or clone repo into your main project folder in the same directory where you have composer.json

### build containers

    docker compose build -d

### enter app container

    docker exec -it app bash

### run commands in app container to build composer and node packages

    composer install

    php artisan migrate

    php artisan db:seed

    npm install

    npm run dev
