Zabbix
======

[![Build Status](https://api.travis-ci.org/azmelanar/ansible-zabbix.png)](https://travis-ci.org/azmelanar/ansible-zabbix) [![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-zabbix-blue.svg?style=flat)](https://galaxy.ansible.com/list#/roles/2593)

Role for install and manage zabbix agent and server.

Requirements
------------

Tested with Ansible 1.8.2

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Example of usage:

    - hosts: servers
      roles:
         - { role: azmelanar.zabbix }

License
-------

MIT

Feedback, improvements, bugs
----------------------------

Please use [issues](https://github.com/azmelanar/ansible-zabbix/issues).
