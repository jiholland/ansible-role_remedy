Role Name
=========

Role for creating asset in BMC Remedy based on gathered facts.

Requirements
------------

BMC Remedy Version [9.1.10] >

Role Variables
--------------

- remedy\_fqdn
- remedy\_port
- creadentials
- login
- logout
- read\_asset
- create\_asset
- system\_role
- assetlifecyclestatus
- catagory
- catagory\_type

Dependencies
------------

None.

Example Playbook
----------------

    ---
    - name: create target as asset in bmc remedy
      hosts: "{{ target }}"
      gather_facts: true

      roles:
        - bmc_asset

License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
