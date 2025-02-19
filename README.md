This package is a fork of instaclick/php-webdriver that works with newer
versions of Selenium.

# WebDriver for Selenium 2
This WebDriver client implementation is based on Meta/Facebook's original [php-webdriver](https://github.com/instaclick/php-webdriver/tree/upstream)
project by Justin Bishop. Meta/Facebook's current [php-webdriver](https://github.com/php-webdriver/php-webdriver) is a complete rewrite.

Distinguishing features:
* Up-to-date with [WebDriver: W3C Editor's Draft 25 Octoberl 2022](https://w3c.github.io/webdriver/)
* Up-to-date with [Selenium 2 JSON Wire Protocol](https://github.com/SeleniumHQ/selenium/blob/trunk/java/src/org/openqa/selenium/remote/DriverCommand.java) (including WebDriver commands yet to be documented).
* In the *master* branch, class names and file organization follow PSR-0 conventions for namespaces.
* Coding style follows PSR-1, PSR-2, and Symfony2 conventions.
* Auto-generate API documentation via [phpDocumentor 2.x](http://phpdoc.org/).

[![Latest Stable Version](https://poser.pugx.org/instaclick/php-webdriver/v/stable.png)](https://packagist.org/packages/instaclick/php-webdriver)
[![Total Downloads](https://poser.pugx.org/instaclick/php-webdriver/downloads.png)](https://packagist.org/packages/instaclick/php-webdriver)

## Links
* [Packagist](http://packagist.org/packages/instaclick/php-webdriver)
* [Github](https://github.com/instaclick/php-webdriver)
* [W3C/WebDriver](https://github.com/w3c/webdriver)

## Notes
* The *5.2.x* branch is no longer maintained. This branch features class names and file re-organization that follow PEAR/ZF1 conventions. Bug fixes and enhancements from the master branch likely won't be backported.
