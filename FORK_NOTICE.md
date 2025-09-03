# Fork Notice

This repository is a fork of [rinvex/laravel-support](https://github.com/rinvex/laravel-support).

## Reason for Fork

The original package was abandoned and needed updates for:
- Laravel 12 compatibility
- PHP 8.3+ support
- Modern dependency versions

## Changes Made

1. **Namespace Change**: `Rinvex\Support` → `Iutrace\Support`
2. **Package Name**: `rinvex/laravel-support` → `iutrace/laravel-support`
3. **PHP Version**: Updated minimum requirement to PHP 8.3
4. **Laravel Version**: Updated to support Laravel 11 and 12
5. **Dependencies**: Updated all dependencies to their latest compatible versions
6. **Documentation**: Updated README and package information

## Migration Guide

If you're migrating from the original package:

1. Update your composer.json:
   ```bash
   composer remove rinvex/laravel-support
   composer require iutrace/laravel-support
   ```

2. Update namespace imports in your code:
   ```php
   // Old
   use Rinvex\Support\Traits\HasSlug;
   
   // New
   use Iutrace\Support\Traits\HasSlug;
   ```

3. Update service provider references if manually registered:
   ```php
   // Old
   Rinvex\Support\Providers\SupportServiceProvider::class
   
   // New
   Iutrace\Support\Providers\SupportServiceProvider::class
   ```

## Original Authors

All credit for the original work goes to:
- Rinvex LLC
- Abdelrahman Omran
- The Laravel Community

## License

This fork maintains the original MIT license.