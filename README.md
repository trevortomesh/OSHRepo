# Repository Title [version number]
===================================
[![License](https://poser.pugx.org/phpunit/phpunit/license)](https://packagist.org/packages/phpunit/phpunit)

This is where you describe your project in short. This will be where potential users look to understand what your project is about -- and it's your chance to catch their eye. It's a good idea to put some sort of picture of your completed project here like this: 

![alt text][logo]

[logo]: https://github.com/trevortomesh/OSHRepo/blob/master/src/img/img1.jpg "Logo Title Text 2"



Requirements and Materials
============

This is where you talk about what sort of libraries are required and what sort of hardware is needed:

Software:
* arduino-example-library
* gcc-c++

Bill of Materials:
* 4 x push buttons
* 12 x green LEDs
* 1 x 4.7k resistor
* 4 x 100 ohm resistor
* 1 x slide switch
* 1 x battery holder
* 1 x breadboard

Installation
============

    composer require buonzz/laravel-4-freegeoip:dev-master

Add the service provider and facade in your config/app.php

Service Provider

    Buonzz\GeoIP\Laravel4\ServiceProviders\GeoIPServiceProvider

Facade

    'GeoIP'            => 'Buonzz\GeoIP\Laravel4\Facades\GeoIP',


Usage
=====

Get country of the visitor

    GeoIP::getCountry();  // returns "United States"
    
Get country code of the visitor

    GeoIP::getCountryCode();  // returns "US"

Get region of the visitor


Credits
=======

* Alexandre Fiori for the awesome http://freegeoip.net web api
* MaxMind for the data
