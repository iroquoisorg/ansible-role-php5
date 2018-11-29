# php5

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-php5.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-memcached)

Ansible role for php5

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.php5`

# Default settings

```

php_extensions:
  - php5.6-cli
  - php5.6-gd
  - php5.6-pgsql
  - php5.6-mysql
  - php5.6-curl
  - php5.6-intl
  - php5.6-mcrypt
  - php5.6-dev
  - php5.6-mbstring
  - php5.6-dom
  - php5.6-bcmath
  - php-pear

pecl_extensions: []

php_ini_lines: []

```
