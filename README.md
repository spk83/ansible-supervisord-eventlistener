spk83.supervisord-eventlistener
===============================

[![Build Status](https://travis-ci.org/spk83/ansible-supervisord-eventlistener.svg?branch=master)](https://travis-ci.org/spk83/ansible-supervisord-eventlistener)

Template role for installing a eventlistener within supervisord

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - spk83.supervisord-eventlistener
```

License
-------

MIT

Author Information
------------------

Vishal Shah <vishal.shah@nyu.edu>
