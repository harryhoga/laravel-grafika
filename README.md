# Laravel- Grafika

Package is a simple service provider for [Grafika library](https://kosinix.github.io/grafika/). A beautiful library will images

## Install

Begin by installing this package through Composer. Edit your project's composer.json file to require harryhoga/laravel-grafika.

"require": {
"hoga/laravel-grafika": "dev-master"
}
Next, update Composer from the Terminal:

composer update

OR in bash

```bash
$ composer require hoga/laravel-grafika --prefer-dist
```

### 2 - Provider

Next, add your new provider to the providers array of config/app.php:

    'providers' => [
        // Other service providers...
    	Hoga\Grafika\Providers\GrafikaServiceProvider::class,
    ],

### Example

# laravel-grafika
