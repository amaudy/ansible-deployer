Deploy User
=========

- Create Linux User on remote server for deployment
- User no root permission
- Copy deploy key to server
- Copy "authorized_keys" to home directory


Role Variables
--------------

- User
- authorized_keys' file
- Deploy key (both private and public key)

Dependencies
------------

It should create deploy folder and give fully permission to deploy user

This suppose to be another role

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
