# ansible-role-docker

This role install Docker on target system

Requirements
------------

Python 3.5 or above (Ansible 2.5 requirement).

Dependencies
------------

See `meta/main.yml` for other roles dependencies

Example Playbook
----------------

```yaml
---
- hosts: all
  roles:
    - ansible-role-docker
```

Tests
-----

Test are made via Molecule and TestInfra. They will be automatically ran by the CI after every push.

Author Information
------------------

Florian Furlanetto - ffurlanetto@adneom.com
