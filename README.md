🧾 bmc\_asset
============

Role for creating asset in BMC Remedy based on gathered facts from Cisco Catalyst and Nexus devices.

Requirements
------------

BMC Remedy Version 9.1.10> (tested).

Role Variables
--------------

- remedy\_fqdn
- remedy\_port
- remedy\_username
- remedy\_password

Dependencies
------------

None.

Example Playbook
----------------

    ---
    - name: Create asset in BMC remedy based on gathered facts from target.
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
