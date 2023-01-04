Role Name
=========
Apache server configure, apache roll will help to deploy the web server.

Requirements
------------

This roll work for RHEL faimly. before deploy the roll hosts should be configured in master machine or ansible server machine.

Role Variables
--------------

variables that are in defaults/main.yml,

    ansistrano_deploy_from: "/home/chandrashekhar/.ansible/roles/apache"
    ansistrano_deploy_to: "/var/www/ansistrano-demo"

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

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

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
