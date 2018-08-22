# Laravel Nova / Laravel Cashier

This package adds several components to your Laravel Nova Admin panel to help you with managing customer subscriptions, it works hand
in hand with [Laravel Cashier](https://github.com/laravel/cashier).

## How it works

This package adds a section in the billable resource details view with some information about the subscription:

## Installation and usage

You may require this package using composer:

```
composer require themsaid/nova-cashier-manager
```

Now in your billable resource, let's say User, add the following to the `fields()` method:

```
CashierResourceTool::make()->onlyOnDetail()
```


## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
