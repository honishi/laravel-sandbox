setup
--
````
curl -sS https://getcomposer.org/installer | php
sudo apt-get install php5-mcrypt
./composer.phar create-project laravel/laravel hello --prefer-dist
````

kick
--
````
php artisan serve --host 0.0.0.0 --port 8000
````
