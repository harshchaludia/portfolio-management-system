<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>

<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>

## Portfolio Management System

This portfolio framework is a premium module outlined to empower you, to orchestrate your ventures and display your works for the guests of your site. It can used as a catalogue too for any kind of motives. This system permits you to form a full portfolio of your works and experiences, along with your profile. All your works will be divided into categories which are, in their turn, are partitioned into sections. Each portfolio features is a brief depiction which is shown within the list of categories.

Features:
- Authentication Modules.
- Image upload.
- Update/ Edit fields.
- A starter template to implement any project from scratch.

## Database

A sample "test.sql" file is attached with this project, to get started.

## Screenshots

<p float="center">
  <img src="https://github.com/harshchaludia/portfolio-management-system/blob/master/screenshots/dashboard.PNG" width="24%" />
  <img src="https://github.com/harshchaludia/portfolio-management-system/blob/master/screenshots/about.PNG" width="24%" /> 
  <img src="https://github.com/harshchaludia/portfolio-management-system/blob/master/screenshots/projects.PNG" width="24%" />
  <img src="https://github.com/harshchaludia/portfolio-management-system/blob/master/screenshots/experience.PNG" width="24%" />
    </p>
    <br>
    <p float="center">

  <img src="https://github.com/harshchaludia/portfolio-management-system/blob/master/screenshots/blog.PNG" width="24%" />
  <img src="https://github.com/harshchaludia/portfolio-management-system/blob/master/screenshots/services.PNG" width="24%" />
  <img src="https://github.com/harshchaludia/portfolio-management-system/blob/master/screenshots/contact.PNG" width="24%" />
      <img src="https://github.com/harshchaludia/portfolio-management-system/blob/master/screenshots/skills.PNG" width="24%" />

</p>


## Implementation


#### Clone this repo:
```
git clone https://github.com/harshchaludia/portfolio-management-system.git
```

#### Install php dependencies:
```
composer install
```

#### Install javascript dependencies:
```
yarn
```
Or, if you like pain and suffering:
```
npm install
```

#### Set up database connections
Edit the .env file attached with this project.
add the mysql details, to get started.

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=test
DB_USERNAME=root
DB_PASSWORD=

```

#### Run database migrations
```
php artisan migrate
```

#### Serving the project

```
php artisan serve

```

#### Login and access project
 <br>
    <p align="center">

  <img src="https://github.com/harshchaludia/portfolio-management-system/blob/master/screenshots/login.PNG" width="30%" />
  <img src="https://github.com/harshchaludia/portfolio-management-system/blob/master/screenshots/register.PNG" width="30%" />


</p><br>

Login modules are implemented underlying Laravel instance. To singUp, simply hit the /register route. To singIn, simply hit the /login route. A user will be logged in and you will be redirected to /admin.

#### Build resources:
```
gulp
```
CSS and JS will be built and moved into the vendor laravel instance automatically.

#### Watch for changes and build automatically:
````
gulp watch
````


## Contributing

Developers need contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

The Laravel community is welcoming to all, hence please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within this project, please send an e-mail via [harshchaludia@gmail.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
