# Ansible Role: Install modman

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-modman.svg)](https://travis-ci.org/tschifftner/ansible-role-modman)

Installs modman on Debian/Ubuntu linux servers. Installs cronjob to sel-update

## Requirements

ansible 1.8+

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
## Supported OS
Ansible          | Debian Jessie    | Ubuntu 14.04    | Ubuntu 12.04
:--------------: | :--------------: | :-------------: | :-------------: 
1.8              | Yes              | Yes             | Yes
1.9              | Yes              | Yes             | Yes
2.0              | Yes              | Yes             | Yes


## License

MIT / BSD

## Author Information

 - Tobias Schifftner, @tschifftner