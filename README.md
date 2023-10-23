<p align="center"><a href="https://laravel.com" target="_blank"><img src="public/readme-images//laravel_administration.jpg" width="800" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel Administration

Laravel Administration library provides the facility to developer to create only model. Then if developer use the LaravelAdmin Trait in that model then, he/she not need to perform the crud operations like create routes, views and controller logics. Laravel administration will provide autometically crud operations, you can check from your interface by requesting the URL app-base-url/admin.

If developer use the LaravelAdminAPI trait in model. Then laravel administration package will provide the all apis for crud, developer not need to perform create, read, list and delete apis for that model. Developer only need to get the model id and set that model ID into Postman attached collection and test the all apis after authentication.

## Installation and Usage Instructions

You can install and use package by performing these instructions
<h3>Create AUTO CRUD</h3>
<ol>
    <li><b>composer require create-project laravel/laravel LaravelAdministration</b></li>
    <li>Migration the migrations files and seed <b>Php artisan migrate:fresh --seed</b></li>
    <li>To make new Model with Migration <b>php artisan make:model DemoTester -m </b></li>
    <li>Inside the DemoCRUD model add Trait in this way <b>use LaravelAdmin</b></li>
    <li>You can edit migration <b>Make Fields of DemoTester like, teser_name, tester_email, tester_image, tester_is_verified</b></li>
    <li>You can serve <b>php artisan serve</b></li>
    <li>Go to url <b>base-url/admin</b></li>
    <li>Login and Go to <b>base-app-url/admin/crud</b></li>
    <li>You can view</li>
</ol>



You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**
- **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
- **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
"# CreateReadMe" 
