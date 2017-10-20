# google-oauth-php
Old version Google OAuth library for use in PhpCodeIgniter 3

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require meliorator/google-oauth-php
```

or add

```
"meliorator/google-oauth-php": "^0.1.0"
```

to the require section of your `composer.json` file. 

Usage
--------
Copy class Gooleplus from application/libraries/Googleplus.php to [root project]/application/libraries and copy config application/config/googleplus.php to [root project]/application/config directory

for invoke Google OAuth use follow code

```php
$this->googleplus->loginURL()

```
