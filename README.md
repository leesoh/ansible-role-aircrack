Aircrack-ng
=========

Ansible role to install Aircrack-ng from source.

Requirements
------------

None

Role Variables
--------------

aircrack_git_location: "/opt"

Dependencies
------------

leesoh.git

Example Playbook
----------------

```yml
- hosts: servers
  roles:
      - leesoh.aircrack-ng
```

License
-------

BSD-3

Author Information
------------------

https://www.aircrack-ng.org