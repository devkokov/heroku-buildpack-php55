# Heroku buildpack: PHP 5.5

Heroku has dropped support for PHP 5.5 in their official buildpack.

This is a fork of v127 of Heroku's PHP Buildpack, which has support for PHP 5.5

This has only been tested on Dokku, and is not guaranteed to work on Heroku.

## Usage

Add Heroku PHP Buildpack (v127) as a dependency in your application:

    composer require heroku/heroku-buildpack-php:127

Set the BUILDPACK_URL:

    BUILDPACK_URL=https://github.com/devkokov/heroku-buildpack-php55
