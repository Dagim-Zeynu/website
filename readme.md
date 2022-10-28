<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

##                                        To run this app
- Run `composer install`
- Run `NPM install`
- Connect with MySQL database
- Create `.env` file
  - Generate key `APP_KEY` with `php artisan key:generate`
  - Update database connection info
- Run `php artisan migrate`
- Seed the database
  - Run `php artisan db:seed`
- Run `php artisan storage:link`
- Set up Apache web server
