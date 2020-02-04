hoplacloud.postfix
=========

Hopla.cloud role for ansible to install and configure postfix.

Install and configure a postfix server with reverse dns. The server can send mail from localhost only.


Requirements
------------

Linux server Ubuntu 18.04 / CentOS 7

Role Variables
--------------

```
user_name: system sudo user
user_email: contact email
```

Dependencies
------------

Nona.

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

Joffrey Skandera for [hopla.cloud](https://hopla.cloud)
