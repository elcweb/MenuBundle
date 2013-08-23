Getting Started With ElcwebMenuBundle
=====================================

## Prerequisites

This version of the bundle requires Symfony 2.3+.

## Installation

Installation is a quick process:

1. Download ElcwebMenuBundle using composer
2. Enable the Bundle

### Step 1: Download ElcwebMenuBundle using composer

Add ElcwebMenuBundle in your composer.json:

```js
{
    "require": {
        "elcweb/menu-bundle": "dev-master"
    }
}
```

Now tell composer to download the bundle by running the command:

``` bash
$ php composer.phar update elcweb/menu-bundle
```

Composer will install the bundle to your project's `vendor/elcweb` directory.

### Step 2: Enable the bundle

Enable the bundle in the kernel:

``` php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new Elcweb\MenuBundle\ElcwebMenuBundle(),
    );
}
```
