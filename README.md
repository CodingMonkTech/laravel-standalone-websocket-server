## Laravel Websocket Pusher Compatible Server (Skeleten)

## get it up and running.

After you clone this project, do the following:

```bash
# go into the project
cd laravel-ws

# create a .env file
cp .env.example .env

# install composer dependencies
composer update

# generate a key for your application
php artisan key:generate

# create a local MySQL database (make sure you have MySQL up and running)
mysql -u root

> create database laravel-ws;
> exit;

# add the database connection config to your .env file
DB_CONNECTION=mysql
DB_DATABASE=laravel-ws
DB_USERNAME=root
DB_PASSWORD=

# run the migration files to generate the schema
php artisan migrate


## Credits

- This project is based on  [Laravel Websockets](https://github.com/beyondcode/laravel-websockets). 