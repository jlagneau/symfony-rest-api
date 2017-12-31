# symfony-rest-api

[![Build Status](https://travis-ci.org/jlagneau/symfony-rest-api.svg)][1]
[![Coverage Status](https://img.shields.io/coveralls/jlagneau/symfony-rest-api.svg)][2]
[![StyleCI](https://styleci.io/repos/115855906/shield?branch=master)][3]

---

Symfony 3.4 (LTS) RESTful api demo

## Install

```bash
$ curl -sS https://getcomposer.org/installer | php
$ php composer.phar install
```

## Run

If you want to run your development server.

```bash
$ php bin/console server:start
```

And visit [http://localhost:8000/app_dev.php/][4] once the webserver is started.

## Test

Tests are made with behat.

```bash
$ php vendor/bin/behat
```

[1]: https://travis-ci.org/jlagneau/symfony-rest-api
[2]: https://coveralls.io/r/jlagneau/symfony-rest-api
[3]: https://styleci.io/repos/115855906
[4]: http://localhost:8000/app_dev.php/
