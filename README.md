jiholland.remedy
================

Create asset in BMC remedy.

Requirements
------------

None.

Role Variables
--------------

- remedy_fqdn
- remedy_port
- remedy_username
- remedy_password
- remedy_device_type
- remedy_catagory
- remedy_catagory_type
- remedy_name
- remedy_id
- remedy_serial
- remedy_system_role

Dependencies
------------

None.

Example Playbook
----------------
```YAML
---
- name: Create asset in BMC remedy.
  gather_facts: true
  hosts: "{{ target }}"

  roles:
    - jiholland.remedy
```
License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
