abdennnour.bootstrap
=========

Bootstrap Passwordless SSH User

This is useful for the communication between the control node and the target host(s)


ansible-galaxy install abdennour.bootstrap

Requirements
------------

SSHD to be up and running on target host(s).


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

No dependent roles

Example Playbook
----------------

This is how you can use it:

    - hosts: all
      roles:
         - role: abdennour.bootstrap
           bootstrap_username: ansible
           bootstrap_publickey_path: ~/.ssh/id_rsa.pub
          

License
-------

BSD


