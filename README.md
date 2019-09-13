# ansible-role-app-freeradius

## Purpose
Installs freeradius server package and configures it

## Required variables
| name | description |
| ---- | ----------- |
| freeradius_users | list of dict(username, password) |

## Defaulted  variables
| name | value | description |
| ---- | ----- | ----------- |
| freeradius_state | present |  set to absent to remove package|
| freeradius_users | []  | list of dict(username, password) |

## Supported Distros
Ubuntu 18+
