# Someline Starter API Client

[![Latest Version](https://img.shields.io/github/release/libern/someline-starter-api-client.svg?style=flat-square)](https://github.com/libern/someline-starter-api-client/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/libern/someline-starter-api-client/master.svg?style=flat-square)](https://travis-ci.org/libern/someline-starter-api-client)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/libern/someline-starter-api-client.svg?style=flat-square)](https://scrutinizer-ci.com/g/libern/someline-starter-api-client/code-structure)
[![Quality Score](https://img.shields.io/scrutinizer/g/libern/someline-starter-api-client.svg?style=flat-square)](https://scrutinizer-ci.com/g/libern/someline-starter-api-client)
[![Total Downloads](https://img.shields.io/packagist/dt/libern/someline-starter-api-client.svg?style=flat-square)](https://packagist.org/packages/libern/someline-starter-api-client)

Someline Starter API Client is a client for accessing APIs created using [Someline Starter](https://github.com/libern/someline-starter) framework.

## Install

Via Composer

``` bash
$ composer require libern/someline-starter-api-client
```

## Usage

``` php
$restClient = new Libern\Rest\RestClient();
echo $restClient->echoPhrase('Hello, libern!');
```

## Testing

``` bash
$ phpunit
```

## Contributing

Please see [CONTRIBUTING](https://github.com/libern/someline-starter-api-client/blob/master/CONTRIBUTING.md) for details.

## Credits

- [Libern](https://github.com/libern)
- [All Contributors](https://github.com/libern/someline-starter-api-client/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
