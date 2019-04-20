<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Restaurant booking service 

Todo
- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Install

- git clone https://github.com/saodat1998/TeamWork.git -b master teamwork-todo
- cd teamwork-todo
- cp .env.example .env
- composer install
- php artisan key:generate
- php artisan migrate --seed
- add new local domain to `nginx conf` file (`/public` folder)
- add new local domain your hosts file and open from browser

## Developers

<p align="center">
<a href="https://github.com/saodat1998">@saodat1998</a>
<br>
<a href="https://github.com/ummatoy">@ummatoy</a>
</p>

## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
