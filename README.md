# php-fixer
php-fixer is a pre-commit hook for [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)

Script needs PHP-CS-Fixer, so you need to install it before using it with brew, port or composer.

Just copy pre-commit file under your projects .git/hooks directory or run 
`make install` and enter your project root path.

It supports .php_cs config file if you have one. If not it fixes with level psr2



FAQ
---------
 
 * Nothing happens when i commit
 If nothing happens, check pre-commit file chmod and set to +x.

 * Cannot find php-cs-fixer executable
 Make sure you have installed php-cs-fixer and check it's bin name. It checks bin and vendor/bin directory.

 * I have a .php_cs and nothing happens
 Check your configuration file and look https://github.com/FriendsOfPHP/PHP-CS-Fixer/blob/1.11/README.rst for details
 
