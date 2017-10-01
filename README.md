Freeswitch
==========

Freeswitch Role for Kazoo Ansible

Requirements
------------

None

Role Variables
--------------

User Variables
- kazoo_freeswitch_version - The Kazoo Freeswitch version to install from the 2600hz repo. 
kazoo-ansible manages the version by default.

Dependencies
------------

Roles
- kazoo-ansible.haproxy

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: kazoo-ansible.freeswitch }

License
-------

MIT

