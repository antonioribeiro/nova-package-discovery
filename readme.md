# Nova Package Discovery package

Discover new packages! Check out the ten most recent and most popular packages on NovaPackages.com, and also check out some stats about the number of packages submitted and more.
 
<img width="474" alt="image" src="https://user-images.githubusercontent.com/151829/44622253-14538480-a883-11e8-896c-55b08a5c1280.png">

 
 ## Installation

You can install the package in to a Laravel app that uses [Nova](https://nova.laravel.com) via composer:

```bash
composer require tightenco/nova-package-discovery
```

Next, you must register the card with Nova. This is typically done in the `cards` method of the `NovaServiceProvider`.

```php
// in app/Providers/NovaServiceProvider.php

// ...
public function cards()
{
    return [
        // ...
        new \Tightenco\NovaPackageDiscovery\NovaPackageDiscovery,
    ];
}
```
