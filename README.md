# Iutrace Laravel Support

**Laravel support** helpers, contracts, and traits. Validator functionality, and basic controller included out-of-the-box.

[![Packagist](https://img.shields.io/packagist/v/iutrace/laravel-support.svg?label=Packagist&style=flat-square)](https://packagist.org/packages/iutrace/laravel-support)
[![License](https://img.shields.io/packagist/l/iutrace/laravel-support.svg?label=License&style=flat-square)](https://github.com/iutrace/laravel-support/blob/main/LICENSE)

## Fork Information

This package is a fork of the abandoned [rinvex/laravel-support](https://github.com/rinvex/laravel-support) package, updated for Laravel 12 and PHP 8.3+ compatibility.

> **Note:** This package contains complementary generic functionality and may not respect SemVer during major Laravel version transitions.


## Installation

Install via `composer require iutrace/laravel-support`


## Usage

### `mimetypes()` helper

The `mimetypes` method gets valid mime types:
```php
$mimetypes = mimetypes();
```

### `timezones()` helper

The `timezones` method gets valid timezones:
```php
$timezones = timezones();
```

### unique_with Validator Rule

This feature contains a variant of the `validateUnique` rule for Laravel, that allows for validation of multi-column UNIQUE indexes.

It was forked and merged from the awesome [felixkiss/uniquewith-validator](https://github.com/felixkiss/uniquewith-validator) package, which at the time been outdated and un-maintained for a long time. Many thanks to core contributors for developing this.


## Changelog

Refer to the [Changelog](CHANGELOG.md) for a full history of the project.


## Support

For support, please use:

- [GitHub Issues](https://github.com/iutrace/laravel-support/issues)


## Contributing & Protocols

Thank you for considering contributing to this project! The contribution guide can be found in [CONTRIBUTING.md](CONTRIBUTING.md).

Bug reports, feature requests, and pull requests are very welcome.

- [Versioning](CONTRIBUTING.md#versioning)
- [Pull Requests](CONTRIBUTING.md#pull-requests)
- [Coding Standards](CONTRIBUTING.md#coding-standards)
- [Feature Requests](CONTRIBUTING.md#feature-requests)
- [Git Flow](CONTRIBUTING.md#git-flow)


## Security Vulnerabilities

If you discover a security vulnerability within this project, please create a GitHub issue. All security vulnerabilities will be promptly addressed.


## Credits

This package is a fork of the original [rinvex/laravel-support](https://github.com/rinvex/laravel-support) package by Rinvex LLC. We thank the original authors for their excellent work.


## License

This software is released under [The MIT License (MIT)](LICENSE).

(c) 2024 iutrace, Some rights reserved.
Original work (c) 2016-2022 Rinvex LLC, Some rights reserved.
