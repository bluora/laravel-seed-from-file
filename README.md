# Laravel Seed From File

Provides the ability to import data from a file or from files found in the supplied folder.

[![Latest Stable Version](https://poser.pugx.org/bluora/laravel-seed-from-file/v/stable.svg)](https://packagist.org/packages/bluora/laravel-seed-from-file) [![Total Downloads](https://poser.pugx.org/bluora/laravel-seed-from-file/downloads.svg)](https://packagist.org/packages/bluora/laravel-seed-from-file) [![Latest Unstable Version](https://poser.pugx.org/bluora/laravel-seed-from-file/v/unstable.svg)](https://packagist.org/packages/bluora/laravel-seed-from-file) [![License](https://poser.pugx.org/bluora/laravel-seed-from-file/license.svg)](https://packagist.org/packages/bluora/laravel-seed-from-file)

[![Build Status](https://travis-ci.org/bluora/laravel-seed-from-file.svg?branch=master)](https://travis-ci.org/bluora/laravel-seed-from-file) [![StyleCI](https://styleci.io/repos/76907203/shield?branch=master)](https://styleci.io/repos/76907203) [![Test Coverage](https://codeclimate.com/github/bluora/laravel-seed-from-file/badges/coverage.svg)](https://codeclimate.com/github/bluora/laravel-seed-from-file/coverage) [![Issue Count](https://codeclimate.com/github/bluora/laravel-seed-from-file/badges/issue_count.svg)](https://codeclimate.com/github/bluora/laravel-seed-from-file) [![Code Climate](https://codeclimate.com/github/bluora/laravel-seed-from-file/badges/gpa.svg)](https://codeclimate.com/github/bluora/laravel-seed-from-file) 

This package has been developed by H&H|Digital, an Australian botique developer. Visit us at [hnh.digital](http://hnh.digital).

## Install

Via composer:

`$ composer require-dev bluora/laravel-seed-from-file ~1.0`

Enable the service provider by editing config/app.php:

```php
    'providers' => [
        ...
        Bluora\LaravelSeedFomFile\ServiceProvider::class,
        ...
    ];
```

## Usage

`# php artisan db:seed-from-file {dir} {--connection}`

* {dir} - A file or a directory.
* {--connection} - Set the connection that will be used when importing. Defaults to `Config::get('default')`.

## Contributing

Please see [CONTRIBUTING](https://github.com/bluora/laravel-seed-from-file/blob/master/CONTRIBUTING.md) for details.

## Credits

* [Rocco Howard](https://github.com/therocis)
* [Lucas Mezêncio](https://github.com/lucasmezencio)
* [All Contributors](https://github.com/bluora/laravel-seed-from-file/contributors)

## License

The MIT License (MIT). Please see [License File](https://github.com/bluora/laravel-seed-from-file/blob/master/LICENSE) for more information.
