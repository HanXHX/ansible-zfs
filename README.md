Ansible ZFS role
================

[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-HanXHX.zfs-blue.svg)](https://galaxy.ansible.com/HanXHX/zfs/) [![Build Status](https://travis-ci.org/HanXHX/ansible-zfs.svg?branch=master)](https://travis-ci.org/HanXHX/ansible-zfs) 

Install ZFS on Debian Linux.

Requirements
------------

None.

Role Variables
--------------

- `zfs_reboot_on_restart`

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: HanXHX.zfs }

License
-------

GPLv2

Author Information
------------------

- Twitter: [@hanxhx_](https://twitter.com/hanxhx_)
