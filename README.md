hoplacloud.postfix
=========
draxalene.postfix

draxalene role for ansible to install and configure postfix. (by hopla.cloud)

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

None.

Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - draxalene.postfix

License
-------

GPLv3

Author Information
------------------

Alexandre MOREAU by hopla.cloud
