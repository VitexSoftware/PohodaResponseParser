# PohodaResponseParser

[![Build Status][ico-travis]][link-travis]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Total Downloads][ico-downloads]][link-downloads]
[![Latest Version on Packagist][ico-version]][link-packagist]

Library for parsing Pohoda import response XML.
## Install via Composer

``` bash
composer require Hexako/PohodaResponseParser
```

## Usage

``` php
$skeleton = new Skeleton();
echo $skeleton->echoPhrase('Hello, League!');
```

## Rules for contributing

- **1 PR per feature**
- PR with tests are more likely to be merged 
- **tests and coding standard must pass**

```bash
vendor/bin/phpcs -p --standard=PSR2 src tests
vendor/bin/phpunit
```

**Happy coding**!

[ico-version]: https://img.shields.io/packagist/v/Hexako/PohodaResponseParser.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/Hexako/PohodaResponseParser/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/Hexako/PohodaResponseParser.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/Hexako/PohodaResponseParser.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/Hexako/PohodaResponseParser.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/Hexako/PohodaResponseParser
[link-travis]: https://travis-ci.org/Hexako/PohodaResponseParser
[link-scrutinizer]: https://scrutinizer-ci.com/g/Hexako/PohodaResponseParser/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/Hexako/PohodaResponseParser
[link-downloads]: https://packagist.org/packages/Hexako/PohodaResponseParser
