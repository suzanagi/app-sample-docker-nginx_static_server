# Sample program to use Docker
This program is used for demonstrating the usage of docker.
The main mechanism of this work is just to publish the static HTML page in the src directry (index.html) on the nginx server.
The program is made by following the instruction provided by the page [Dockerによる開発環境構築（Mac + Nginx + PHP-FPM + MySQL）Part 1](https://www.no-title.com/web/docker-mac-nginx-php-fpm).

## Summary of the commands
 - start up the docker container by following the yml file (in the top directry): **docker-compose up**
   You can add "-d" option to activate as a background process.
 - stop the running docker container: **docker-compose stop**
 - list up the container: **docker ps**
   You can use "-a" option to show the containers already already been stopped