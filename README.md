naemon
======

Installs and configures Naemon.

Requirements
------------

This role requires Ansible 1.6 or higher.

Role Variables
--------------

| Name          | Default | Description                  |
|---------------|---------|------------------------------|
|naemon_version | 1.0.4   | Version of Naemon to install |

Dependencies
------------

None

Example Playbook
----------------

Install Naemon
```
- hosts: all
  roles:
      - kbrebanov.naemon
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
