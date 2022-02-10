# Set up enviroment for laravel project
PHP 7.4;
MYSQL 8.0.27;
REDIS lastest;
PHPMYADMIN 5.1;

# How to start

1. Clone this project
2. Create "Mysql" folder into this project
3. Push your laravel project into "src" folder
4. Find docker-compose.yml -> services -> nginx: rename first line of volumes like your project name
5. Set up your database, .env file
6. Open terminal, running at first time: sudo docker-compose build && docker-compose up -d
7. Open web browser, go to localhost:8088 // Access phpmyadmin: go to localhost:8081
