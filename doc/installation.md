# Installation

## Requirements
Before installing **Gitea for PHP**, you need to make sure you have [PHP](https://secure.php.net)
and [Composer](https://getcomposer.org), the PHP package manager, up and running.

!!! warning
    Gitea for PHP requires PHP >= **7.2.0**.
    
You can verify if you're already good to go with the following commands:

```shell
php --version
# PHP 7.2.10-0ubuntu1 (cli) (built: Sep 13 2018 13:38:55) ( NTS )

composer --version
# Composer version 1.7.3 2018-11-01 10:05:06
```

!!! info
    If you plan to play with the package sources, you will also need
    [Robo](https://robo.li) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material).

## Installing with Composer package manager

### 1. Install it
From a command prompt, run:

```shell
composer require sab-international/gitea
```

### 2. Import it
Now in your [PHP](https://secure.php.net) code, you can use:

```php
<?php
use Gitea\{Repository, Team, User};
```
