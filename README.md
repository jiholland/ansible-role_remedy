jiholland.remedy
================

Create asset in BMC Remedy.

Requirements
------------

None.

Role Variables
--------------

- remedy\_fqdn
- remedy\_port
- remedy\_username
- remedy\_password
- remedy\_asset

Dependencies
------------

None.

Example Playbook
----------------
```YAML
---
- name: Create asset in BMC remedy.
  hosts: "{{ target }}"
  gather_facts: true

  roles:
    - jiholland.remedy
```
License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
