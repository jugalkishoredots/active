Active for Laravel

The helper class for Laravel applications to get active class base on current url.

Since version 7.0, the major version of this library will match the major version of Laravel.

| Laravel version | Active library version  |
| --------------- | ----------------------- |
| >= 7.x          | >= 7.x                  |


## Installation

Require this package as your dependencies:

```
composer require /active
```
> If you are using Laravel 5.5+, you do not need to manually register the ServiceProvider and Alias.

Append this line to your `providers` array in `config/app.php`

```php
Dotsquares\Active\ActiveServiceProvider::class,
```

Append this line to your `aliases` array in `config/app.php`

```php
'Active' => Dotsquares\Active\Facades\Active::class,
```


## Changelog:

* v1.0: support Laravel 10 and start using the same marjor version with Laravel

