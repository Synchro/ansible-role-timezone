Timezone (Ansidev)
=========
[![Build Status](https://travis-ci.org/Ilyes512/ansible-role-timezone.svg)](https://travis-ci.org/Ilyes512/ansible-role-timezone)

This role configure's the systems timezone for Ubuntu Trusty (14.04).

Requirements
------------

No requirements.

Role Variables
--------------

`locale_timezone`. Set it to the [IANA time zone name](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones), such as `Europe/Amsterdam` or `Etc/UTC` (the default).

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
