Role Name
=========

Role for adding asset to BMC Remedy based on gathered facts from Cisco network-devices.

Requirements
------------

BMC Remedy Version [9.1.10] >

Role Variables
--------------

- remedy\_host
- remedy\_port
- remedy\_username\_and\_password
- remedy\_api
- remedy\_asset
- remedy\_get\_asset
- remedy\_add\_asset
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
    - name: add target to bmc remedy
      hosts: "{{ target }}"
      gather_facts: false

      roles:
        - role: bmc_asset
          tags: asset

License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
