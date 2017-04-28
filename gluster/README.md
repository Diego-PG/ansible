Gluster
=========

Rol de instalación de Guster, que configura replicación entre todos los host
proporcionados.

Requirements
------------

Actualmente solo funciona con derivados de RedHat, pero está pensado para
añadir soporte a más plataformas.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

Example Playbook
----------------

---
- hosts: gluster
  remote_user: ansible
  become: yes
  roles:
    - role: gluster

License
-------

MIT

Author Information
------------------

Diego Prieto
https://github.com/Diego-PG
