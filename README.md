# Ansible Role: Install yarn

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-yarn.svg?branch=master)](https://travis-ci.org/tschifftner/ansible-role-yarn)

Installs yarn from source on Debian/Ubuntu linux servers.

## Requirements

ansible 2.0+

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

## Dependencies

None.

## Installation

```
$ ansible-galaxy install tschifftner.yarn
```

## Example Playbook

    - hosts: server

      roles:
        - { role: tschifftner.yarn }

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