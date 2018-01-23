Timezone (Ansidev)
=========
[![Build Status](https://travis-ci.org/Ilyes512/ansible-role-timezone.svg)](https://travis-ci.org/Ilyes512/ansible-role-timezone)

This role configure's the systems timezone for Ubuntu Trusty (14.04).

Requirements
------------

No requirements.

Role Variables
--------------

`locale_timezone: Etc/UTC`

Set it to the [IANA time zone name](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones), for example:
* `Etc/UTC` (the default).
* `Europe/Amsterdam`
* `America/Montreal`
* `Etc/GMT-4`

Dependencies
------------

No dependencies.

Example Playbook
----------------
```
- hosts: servers
  roles:
    - { role: ilyes512.timezone, tag: ansidev.timezone }
```

License
-------

MIT

Author Information
------------------

Ilyes Ahidar [@Ilyes512](https://twitter.com/ilyes512)
