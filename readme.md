
## Laravel Auth Login and Angularjs data rendering 
Create new database and update name into .env file 
Create a file .env on root of the project and update
DB_DATABASE=laravel_auth
DB_USERNAME=root
DB_PASSWORD=root

First install all dependencies using

composer install

php artisan migrate:install

Localhost url will look like for new register
http://localhost/laravel_auth/public/register
http://localhost/laravel_auth/public/login