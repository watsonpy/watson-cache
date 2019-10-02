Watson-Cache
============

A collection of cache storage mechanisms that act like a dict.

Currently supporting:

-   Memory
-   File
-   Memcache

Also contains a decorator that can be used within the `watson-framework`
package.

For full documentation please see [Read The
Docs](http://watson-cache.readthedocs.org/).

Build Status
------------

[![Build
Status](https://img.shields.io/travis/watsonpy/watson-cache.svg?maxAge=2592000)](https://travis-ci.org/watsonpy/watson-cache)
[![Coverage
Status](https://img.shields.io/coveralls/watsonpy/watson-cache.svg?maxAge=2592000)](https://coveralls.io/r/watsonpy/watson-cache)
[![Version](https://img.shields.io/pypi/v/watson-cache.svg?maxAge=2592000)](https://pypi.python.org/pypi/watson-cache/)

### Installation

`pip install watson-cache`

### Dependencies

-   watson-common
-   watson-di (for test coverage, and decorator usage)
-   python3-memcached

### Todo

-   Add SqlAlchemy based storage
-   Add Redis based storage
