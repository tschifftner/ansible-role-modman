# Ansible Role: Install modman

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-modman.svg?branch=master)](https://travis-ci.org/tschifftner/ansible-role-modman)

Installs modman on Debian/Ubuntu linux servers. Installs cronjob to sel-update

## Requirements

ansible 2.0+

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```
modman_download_url: 'https://raw.githubusercontent.com/colinmollenhour/modman/master/modman'
modman_destination: '/usr/local/bin/'
```

## Dependencies

None.

## Installation

```
$ ansible-galaxy install tschifftner.modman
```

## Example Playbook

    - hosts: server
      roles:
        - { role: tschifftner.modman }

## Supported OS

 - Debian 9 (Stretch)
 - Debian 8 (Jessie)
 - Ubuntu 18.04 (Bionic Beaver)
 - Ubuntu 16.04 (Xenial Xerus)
 
## Required ansible version

Ansible 2.5+

## License

[MIT License](http://choosealicense.com/licenses/mit/)

## Author Information

 - [Tobias Schifftner](https://twitter.com/tschifftner), [ambimax® GmbH](https://www.ambimax.de)