# flysystem-cloudinary
Adapter for theleague php flysystem for Cloudinary, with methods to support Laravel Voyager Media.

[![Author](https://img.shields.io/badge/author-@thedarkkid-blue.svg?style=flat-square)](https://twitter.com/thedarkkid)
[![Latest Stable Version](https://poser.pugx.org/thedarkkid/cloudinary-flysystem/v/stable)](https://packagist.org/packages/thedarkkid/cloudinary-flysystem) 
[![Total Downloads](https://poser.pugx.org/thedarkkid/cloudinary-flysystem/downloads)](https://packagist.org/packages/thedarkkid/cloudinary-flysystem) 
[![Latest Unstable Version](https://poser.pugx.org/thedarkkid/cloudinary-flysystem/v/unstable)](https://packagist.org/packages/thedarkkid/cloudinary-flysystem) 
[![License](https://poser.pugx.org/thedarkkid/cloudinary-flysystem/license)](https://packagist.org/packages/thedarkkid/cloudinary-flysystem)
[![Build Status](https://travis-ci.org/laryhoFolaranmi/cloudinary-flysystem-adapter.svg?branch=master)](https://travis-ci.org/thedarkkid/cloudinary-flysystem)

Install

```bash
composer require thedarkkid/cloudinary-flysystem
```
Example

```php

use TheDarkKid\Flysystem\Cloudinary\CloudinaryAdapter as Adapter;

$config = [
    'api_key' => ':key',
    'api_secret' => ':secret',
    'cloud_name' => ':name',
];

$container = new Adapter($config);

$filesystem = new League\Flysystem\Filesystem( $container );

```

## List contents and others actions use Filesystem api

```php

$filesystem->listContents()

```


### For use in laravel

[https://github.com/laryhoFolaranmi/cloudinary-flysystem-adapter]


 
 