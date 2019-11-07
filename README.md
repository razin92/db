Role Name
=========

DB role for education goals.
This role installs and configures mongodb for Puma-App.

Requirements
------------

For automated testing:

molecule>=2.6
testinfra>=1.10
python-vagrant>=0.5.15
ansible-lint>=4.1.0

Role Variables
--------------

mongo_port - Port number for mongodb service
mongo_bind_ip - listening ip-address
env - specify current environment

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - db

License
-------

BSD

Author Information
------------------

s_Razin
