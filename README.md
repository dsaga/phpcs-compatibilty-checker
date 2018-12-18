# PHP Compatibility Checker for 7.2

PHP Compatibility Checker for PHP CodeSniffer Via Composer

Clone this repository into the root of any project that you want to inspect for php 7.2 compatibility 

## Steps to install after clone repo

* run composer 

    $ composer update --lock

* verify phpcs is working 

    $ /vendor/bin/phpcs -i


## Executing the checker 

* to check against a particular folder in the current working directory and output to a log file

    $ ./vendor/bin/phpcs -p foldername --report-file=folder-log-errors-php7-2.txt


## Other Resources
* [The original documentation for PHP Compatibility Checker can be found here](https://github.com/PHPCompatibility/PHPCompatibility#installation-in-a-composer-project-method-1)
