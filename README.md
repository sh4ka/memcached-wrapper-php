# PHP 5 wrapper for Memcached

Optimized PHP 5 wrapper for Memcached extension tested and proven to perform under high concurrency conditions on modern websites including but not limited to:

* CollegeHumor
* Vimeo
* Lot18
* Dorkly
* Jest
* Todays Big Thing
* Image Socket

## Features

* Optimized Memcached settings out of the box
* Gracefully handles expiration of cached resources via single request to prevent dogpiling
* Adjustable local storage integration to avoid duplicate lookups during run time
* Automatically switches to IgBinary support if IgBinary is enabled
* 100% phpDocumentator 2 code coverage
* 100% PSR-2 code coverage
* Composer friendly package

## Usage

If you have your autoloader,  update namespaces and drop the files
into your frameworks library.

For people that do not have that setup, you can visit [http://getcomposer.org](http://getcomposer.org) to install
composer on your system. After installation simply run `composer install` in the parent
directory of this distribution to generate vendor/ directory with a cross-system autoloader.

Please see Examples directory for a simple run down of functionality.

## Additional information

Memcached: http://pecl.php.net/package/memcached 
IgBinary: http://pecl.php.net/package/igbinary
