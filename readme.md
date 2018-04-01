<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>


## Laravel Passoprt API

This is the sample for API of Laravel using Passport Auth validation.

Install this project to your machine:
```php
composer install
```

Create database named ```passport```, and settings for your DB:
```php
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=passport
DB_USERNAME=root
DB_PASSWORD=Hh1107030
```

Now setup database configuration for your project:
```php
php artisan migrate
```

For [Postman](https://www.getpostman.com/) help you can download sample API from ```\postman\Passport.postman_collection```

## Learning Laravel

If you are new in laravel then for initial Laravel set up, please follow this [link](https://laravel.com/docs/5.6/installation).

## Learning Passport

For detail documentation of Passport please visit this [link](https://laravel.com/docs/5.6/passport).

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
