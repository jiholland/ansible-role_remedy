remedy
======

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

Dependencies
------------

None.

Example Playbook
----------------

    ---
    - name: Create asset in BMC remedy.
      hosts: "{{ target }}"
      gather_facts: true

      roles:
        - role: remedy
          tags: remedy

License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
