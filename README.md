Role Name
=========

Hopla.cloud role for ansible to install and configure postfix.

Requirements
------------

None.

Role Variables
--------------

None.


Dependencies
------------

- hoplacloud.linux_update
- hoplacloud.linux_motd


Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - hoplacloud.postfix

License
-------

GPLv3

Author Information
------------------

This role was created in 2019 by [hopla.cloud](https://hopla.cloud)
