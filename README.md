# ToDO List Web App

Simple todo web app made for learning purpose

1. Prepare local development setup. This application needs MySQL DB in order to work. Connection details are configured in `conn.php` file. You can use Docker.
You may want to use one of the following options. They all good but please check them before making the decision on what to use:
- https://hub.docker.com/_/mysql  
- https://hub.docker.com/_/mariadb
- https://hub.docker.com/r/bitnami/mysql
- https://hub.docker.com/r/bitnami/mariadb

Make sure you can connect to the database using user and password from the connection string file. You can find preparation scripts in the `migrations` folder. 

2. Once you are able to connect to a database using CLI and username and password from the `conn.php` file, please make sure DB structure is created as well. 
3. DB part is done, get yourself familiar with the code and let's start preparing Nginx+PHP-FPM for running the website. We will use the following instructions: 
- https://hub.docker.com/r/bitnami/php-fpm (The "Serving your PHP app through an nginx frontend" part)
