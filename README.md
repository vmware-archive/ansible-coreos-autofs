CoreOS autofs
=============

This role installs a working autofs service into a CoreOS node

Role Variables
--------------

- coreos_autofs_etc: where to store the autofs maps
- coreos_autofs_install_dir: where to install autofs
- coreos_autofs_systemd: where to install the service file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: coreos
      roles:
         - role: "sigma.coreos-autofs"

License
-------

MIT
