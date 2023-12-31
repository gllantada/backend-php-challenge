<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

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
# Development Challenge for PHP

This challenge aims to evaluate basic skills in PHP development, and a bit of data/entity modeling. The idea is to build an HTTP REST API.

## Functionality

The API has to fulfill the following conditions:
* Endpoints for authentication using JWT.
  Also an endpoint for refreshing the JWT access token.
* Endpoint for retrieving movies.
  It should be allowed to filter and sort by some field.
* Endpoint for retrieving the information (director included) of a specific episode of a TV Show
* Endpoint for adding a new object (it could be for any entity you like).

### Model

Entities to consider:
* Movie<br/>
  Has many actors, but one director.
* TV Show<br/>
  Has many actors, but one director. It also has seasons and episodes inside each of one.
* Actor<br/>
  Can be on different movies and tv shows.
* Director<br/>
  Can direct many movies and specific episodes of tv shows.

Use your common sense (or imagination 😉) to define the descriptive attributes/properties of each entity. For example, name or genre.

## Tech Requirements

These are the following conditions for the development:
* The code should be using **PHP 7 or superior**.
* All the code and comments should be written in **english**.
* Use a **proper naming conventions** and standards when defining the structure of the project and the name of variables, functions, etc.
* Use a **proper structure** to define the different path for the API endpoints.
* Use a framework like Symfony, Laravel, Lumen, CodeIgniter, or any other that you consider appropriate.
* The use of a linter is optional.
* The database could be **relational or NoSQL**, it's up to you. The use of ORM is optional too.
* The database doesn't need to be presented. But the model should be represented in some way. It could be in the form of ORM configuration or at least a minimal documentation or example of some of the entities.

## Presentation

The result of this challenge should be presented as a GitHub or GitLab **private** repository, giving access to the person that contacted you.<br/>
Please add some minimal documentation (in the form of a README file) describing how to run the project and if there is any requirement or consideration to do so.

Oh, and please don't link or fork this repo to create your own. That way other people trying to complete this challenge won't be able to see solutions to it 😆.

Let's code 💻!

