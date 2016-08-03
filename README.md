ansible-role-mediaDirs
=========
[![Travis](https://img.shields.io/travis/louwandre90/ansible-role-mediaDirs.svg?style=flat-square)](https://travis-ci.org/louwandre90/ansible-role-mediaDirs.svg?branch=master)
[![Ansible Role](https://img.shields.io/badge/role-louwandre90.mediaDirs-blue.svg?style=flat-square)](https://galaxy.ansible.com/louwandre90/mediaDirs/)

This role installs directories for the following Media files:
- Downloads
- Movies
- TVShows
- Pictures
- Music

Requirements
------------

None 


Role Variables
--------------

The following defaults are set:

    username: jarvis

To pass different variables:

    ansible-playbook playbook.yml -e 'username=myuser'
    
Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: louwandre90.mediaDirs }

License
-------

BSD

Author Information
------------------

This role was created in 2016 by Andre Louw.
