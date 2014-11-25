HighchartsPhpBundle
===================

A HighchartsPhp Bundle for Symfony

Installation:
-------------
Require the bundle via composer:

    "require": {
		"royopa/highchartsphp-bundle": "master"
	}

Add the bundle to your AppKernel.php:

```php
public function registerBundles()
{
    return array(
        // ...
        new Ghunti\HighchartsPhpBundle\GhuntiHighchartsPhpBundle(),
        // ...
    );
}
```

Usage:
------

### Use as service highcharts:

```php
    //...
    class AcmeController extends Controller
    {
        public function indexAction()
        {

    //...
```
