Docker Role
=========

A light role to install docker on a remote host and also install all prerequistes `python-pip and docker-py` necessary to run a concaiter with the docker_container module 

Requirements
------------
This role has any prerequistes, it can works just on Ubuntu or CentOS Linux distribution

Role Variables
--------------

For this role we just have 01 variable which permit us to modify the name of the remote host if necessary:
ansible_user: root

Dependencies
------------

Any dependency for this role.

Example Playbook
----------------

Find below an example of playbook to use this role:

    - hosts: all
      vars:
        ansible_user: root
      roles:
         - role: steissier.docker_role

License
-------

NONE

Author Information
------------------

`Sebastien Teissier`
