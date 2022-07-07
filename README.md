Role Name
=========

Role for creating asset in BMC Remedy based on gathered facts.

Requirements
------------

BMC Remedy Version 9.1.10> (tested) <br>
Change variables in defaults/main.yml to match your environment.

Role Variables
--------------

defaults:
- remedy\_fqdn
- remedy\_port
- remedy\_username
- remedy\_password

vars:
- remedy\_credentials
- remedy\_login
- remedy\_logout
- remedy\_read\_asset
- remedy\_create\_asset
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
        - role: bmc_asset
          tags: asset

License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
