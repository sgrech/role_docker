Role Name
=========

Ansible role used to install docker and docker-compose on an ubuntu based system (tested on debian 10, ubuntu 18.04 and linux mint 19).

Requirements
------------

None.

Role Variables
--------------

When provisioning role to linux distributions based on debian or ubuntu. but ansible defined variable ansible_distribution_release will not show the distribution it is based upon, use this variable to override:
- host_distribution_release

Use the following variable to override docker-compose version 
- compose_version

Dependencies
------------

None.

Example Playbook
----------------

TODO

License
-------

GPL

Author Information
------------------

TODO
