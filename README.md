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
- remedy\_asset\_name
- remedy\_asset\_id
- remedy\_asset\_serial\_number
- remedy\_asset\_system\_role
- remedy\_asset\_assetlifecyclestatus
- remedy\_asset\_model\_number
- remedy\_credentials
- remedy\_login
- remedy\_logout
- remedy\_read\_asset
- remedy\_create\_asset

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
