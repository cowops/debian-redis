Debian-Redis
============

Redis is an open source, BSD licensed, advanced key-value store

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-redis }

Tasks
-----

  - Install [Redis](http://redis.io/) server

License
-------

BSD
