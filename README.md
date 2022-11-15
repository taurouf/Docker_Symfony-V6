
# Docker Symfony V6 & PHP 8.1

Dockerisation a Symfony V6 project with PHP 8.1

It is composed by 3 containers:
  
  - nginx, acting as the webserver.
  - php, the PHP-FPM container with the 8.0 version of PHP.
  - db, which is the MySQL database container with a MySQL 8.0 image.

  
## Installation

1. Clone my repo
2. ```docker-compose up -docker```
3. ```docker exec www_symfo composer create-project symfony/website-skeleton project```
4. Go to http://127.0.0.1:8080/ for PhpMyAdmin and http://127.0.0.1:8000 for symfony