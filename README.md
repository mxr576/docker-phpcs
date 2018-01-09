Yet an another PHP Codesniffer container
===

### Installed coding standards
* [Drupal Coding Standard](https://packagist.org/packages/drupal/coder) (Drupal, DrupalPractice) - For reviewing Drupal code.
* [PHP Compatibility](https://packagist.org/packages/wimg/php-compatibility) - A set of sniffs that checks for PHP version compatibility.

### Standalone usage example

#### PHPCS (PHP CodeSniffer)

```
docker run -it --rm -v $(pwd):/data mxr576/phpcs phpcs fooo.php
```

#### PHPCBF (PHP CodeFixer)

```
docker run -it --rm -v $(pwd):/data mxr576/phpcs phpcbf fooo.php
```

(Where `fooo.php` is an existing file in the current working directory.)

### PHPStorm usage example
![PHPStorm configuration](https://raw.githubusercontent.com/mxr576/docker-phpcs/master/phpstorm.gif)
