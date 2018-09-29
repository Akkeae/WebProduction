# WebProduction
Requirements
````````````
1. XAMPP for PHP 7.0 and higher (Apache and MySQL)
2. Git bash
3. Composer for php

Installation
``````````
1. Setup and install XAMPP
2. Setup and install Git
3. Setup and install composer
4. copy project folder to directory "xampp/htdocs/"
5. open .env file and check database name
6. create database with same name in mysql
7. open App/Providers/AppServiceProvider
8. comment out the contents of boot function
9. open git bash under project root folder and enter following commands
10. enter "composer update"
11. enter "php artisan key:generate"
12. enter "php artisan cache:clear"
13. enter "php artisan migrate:fresh"
14. remove comment outs in boot function of AppServiceProvider
14. open browser and enter url "localhost/dragongamingapp/public/"

Admin Account
`````````````
username - dggamingapp@gmail.com
password - 123456
