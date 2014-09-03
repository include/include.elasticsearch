Tiny Elasticsearch setup on CentOS
==================================

This tiny Elasticsearch setup is nothing more than this... install, configure and run elasticsearch.

Requirements
------------

None.

Role Variables
--------------

Change variables under `vars/main.yml`. All variables used in this role are mentioned here.

Dependencies
------------

This role installs OpenJDK 1.7.0 if not present.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: include.elasticsearch }

License
-------

BSD

Author Information
------------------

Francisco Cabrita - <francisco.cabrita@gmail.com>