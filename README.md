# Project: xxx  #

# Environment
    php version 8.0.x
    Laravel Framework 8.49.2

### Checkout source code
    clone source from https://github.com/tungnd92/laravel8.x.git

### Install PHP dependence packages
    PHP packages are declared in the file **composer.json**.

        cd <project-dir>
        composer install
### Environment Configuration
Laravel environment configuration in file **.env**.

Copy file **.env.dev** to **.env** and make the appropriate modifications.

    cp -r .env.dev .env

Setting up database information

    DB_HOST=
    DB_PORT=
    DB_DATABASE=
    DB_USERNAME=
    DB_PASSWORD=

Create a key to make the app more secure

    php artisan key:generate

Run App

    php artisan serve

### Laravel IDE Helper Generator
Automatic PHPDocs generation for Laravel Facades

    php artisan ide-helper:generate

Automatic PHPDocs for models
    
    php artisan ide-helper:models







