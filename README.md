Project not in active development!
===

This page was created to help you migrate to [`raml-org/raml-php-parser`](https://github.com/raml-org/raml-php-parser) - the official RAML parser for PHP.

The original work from `alecsammon/php-raml-parser` is moved to [`raml-org/raml-php-parser`](https://github.com/raml-org/raml-php-parser).
All new development, issues and pull requests must be created in the [`raml-org/raml-php-parser`](https://github.com/raml-org/raml-php-parser).

We strongly advise you to update your `composer.json` so it requires the new name and location of the project.
This is backwards compatible with the previous versions 2 and 3 and should be as easy to do as executing:
```
$ composer remove alecsammon/php-raml-parser
$ composer require raml-org/raml-php-parser "^4.0"
```
