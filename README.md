/src/laravel_sample

docker-compose up -d --build

docker exec -it php-laravel bash

php composer.phar install

cp -a .env.example .env

localhost:8600  
-[GENERATE APP KEY]
