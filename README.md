repo-openstack
==============

Ansible role that configure Openstack repository.

Requirements
------------

Only supports RedHat 7 and Ubuntu 16.04.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

    openstack_release: pike
Openstack release installed. Defaults to the latest stable release.

Dependencies
------------

This role has no dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: repo-openstack, openstack_release: 'pike' }

License
-------

Apache

OpenIO
------

This role was created in 2017 by OpenIO.
