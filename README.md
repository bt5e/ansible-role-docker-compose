Ansible Role - Docker Compose - CentOS
======================================

[![Build Status](https://travis-ci.org/bt5e/ansible-role-docker-compose.svg?branch=master)](https://travis-ci.org/bt5e/ansible-role-docker-compose)

Docker Compose install based on: https://docs.docker.com/compose/install/

Requirements
------------

Assumes Docker is installed.

Role Variables
--------------

None.

Dependencies
------------

- bt5e.docker-ce

Example Playbook
----------------

    - hosts: servers
      roles:
         - bt5e.docker-compose

License
-------

MIT

Author Information
------------------

Ben Tse
