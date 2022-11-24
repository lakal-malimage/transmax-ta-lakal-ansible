Role Name
=========

This role will install nginx webserver and deploy the default index.html file which displays the hostname and IP of the server.

Requirements
------------

N/A

Role Variables
--------------

ip : from facts
hostname: from facts

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------
Lakal Malimage
