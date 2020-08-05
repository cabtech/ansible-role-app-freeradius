----
# ansible-role-app-freeradius

## Purpose
Basic installation and configuration of a [Freeradius](https://wiki.freeradius.org/Home) server

## Required variables
| name | description |
| ---- | ----------- |
| freeradius_users | dict of username:password |

## Defaulted  variables
| name | value | description |
| ---- | ----- | ----------- |
| freeradius_etc_dir | `/etc/freeradius` | where the config lives |
| freeradius_pkgs    | [freeradius]      | what to install |
| freeradius_service | freeradius        | what the service is called |
| freeradius_state   | present           | set to absent to remove package|
| freeradius_users   | {}                | dict of username:password |
| freeradius_version | '3.0'             | tells us where the config is |

## To Do
Something better than cleartext passwords

## Supported Distros
Ubuntu 18+ but should be fine on any recent Debian distro

----
