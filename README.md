# PHPStan Sonata

[![Latest Stable Version](https://poser.pugx.org/ekino/phpstan-sonata/v/stable)](https://packagist.org/packages/ekino/phpstan-sonata)
[![Build Status](https://travis-ci.org/ekino/phpstan-sonata.svg?branch=master)](https://travis-ci.org/ekino/phpstan-sonata)
[![Coverage Status](https://coveralls.io/repos/ekino/phpstan-sonata/badge.svg?branch=master&service=github)](https://coveralls.io/github/ekino/phpstan-sonata?branch=master)
[![Total Downloads](https://poser.pugx.org/ekino/phpstan-sonata/downloads)](https://packagist.org/packages/ekino/phpstan-sonata)

## Usage

To use this extension, require it using [Composer](https://getcomposer.org/):

```bash
composer require --dev ekino/phpstan-sonata
```

If you also install [phpstan/extension-installer](https://github.com/phpstan/extension-installer) then you're all set!

<details>
  <summary>Manual installation</summary>

If you don't want to use `phpstan/extension-installer`, include extension.neon in your project's PHPStan config:

```neon
includes:
	- vendor/ekino/phpstan-sonata/extension.neon
```
</details>
