Tiny Elasticsearch setup on CentOS
==================================

A brief description of the role goes here.

This tiny Elasticsearch setup is nothing more than install, configure and run elasticsearch.

Requirements
------------

None.

Role Variables
--------------

Default config variable `elasticsearch_conf` is pointing to `/usr/local/etc/elasticsearch/elasticsearch.yml` you can change this under `vars/main.yml`.

Dependencies
------------

None.

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