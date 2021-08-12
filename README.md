# Isnaad Project 


> Isnaad Project.


## Features

- Laravel 8
- Vue + VueRouter + Vuex + VueI18n + ESlint
- Pages with dynamic import and custom layouts
- Login, register, email verification and password reset
- Authentication with JWT
- Socialite integration
- Bootstrap 4 + Font Awesome 5

## Requirements

- Install Laragon program for database 

## Installation
1-download the project
-  open any termainal you have ex:(cmd , gitbash , powershell)
- `git clone https://github.com/proalaa/Isnad-ye.git`
-  go to project directory -> `cd Isnad-ye`

2- follow these steps after the project is downloaded
- `composer install`
- `cp .env.example .env`
- Edit `.env` and set your database connection details
- `php artisan key:generate` and `php artisan jwt:secret`
- `php artisan migrate`
- `npm install`

## Usage 

#### Development

```bash
# Build and watch
npm run watch

```

[comment]: <> (#### Production)

[comment]: <> (```bash)

[comment]: <> (npm run production)

[comment]: <> (```)

<!-- ## Socialite

This project comes with GitHub as an example for [Laravel Socialite](https://laravel.com/docs/5.8/socialite).

To enable the provider create a new GitHub application and use `https://example.com/api/oauth/github/callback` as the Authorization callback URL.

Edit `.env` and set `GITHUB_CLIENT_ID` and `GITHUB_CLIENT_SECRET` with the keys form your GitHub application.

For other providers you may need to set the appropriate keys in `config/services.php` and redirect url in `OAuthController.php`.

## Email Verification

To enable email verification make sure that your `App\User` model implements the `Illuminate\Contracts\Auth\MustVerifyEmail` contract.

## Testing

```bash
# Run unit and feature tests
vendor/bin/phpunit


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently. -->

## Contributors
- [**Aladdin Mohammed** - *The main maintainer of this project*](https://github.com/proalaa)
- [**Mohammed Al-Raey** - **]

