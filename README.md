Ansible Role: Python
====================

Installs minimal Python 2.7.8 + Setuptools + PIP (from source) on CentOS 6.5

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

* tcosta84.yum

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: tcosta84.python }

License
-------

BSD

Author Information
------------------

This role was created by [Thiago Costa](http://thiagocostapy.com)
