# Docker-php-nginx-mysql
Environment for development with php, niginx and mysql

# How to use
 - Install Docker and docker-compose
 - Execute `git clone https://github.com/guil95/Docker-php-nginx-mysql.git` inside your project
 - Update info in docker-compose and configs for nginx
 - Create an public repository
 - Inside docker directory run `docker-compose up`
 - Update your host with deafult.conf host from the nginx folder, the default is app.local
 
Your project should be organized as follows:
```
project
|
|───docker
│   
└───public
|    │   index.php
|
|___src
```
