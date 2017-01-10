[![Travis Build Status](https://travis-ci.org/hutchic/ansible-infinit.sh.svg?branch=master)](https://travis-ci.org/hutchic/ansible-infinit.sh)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)


Infinit.sh
=========

Install and configures inifinit.sh - a work in progress

Requirements
------------

`ansible > 2.2`

Role Variables
--------------

```
infinit_user: "user"
infinit_user_fullname: "Full Name"
infinit_hub_password: "super secret password"
infinit_volume_mount: "/mnt/infinit"
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: infinit }

License
-------

MIT
