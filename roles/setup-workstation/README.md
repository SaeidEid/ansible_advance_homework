Role Name
=========

setup-workstation: configure work station with flavors, keypairs, security groups...

Requirements
------------

No requirements

Role Variables
--------------

osp_networks: Defintion of private and public networks
osp_router: Definition of public router connecting the networks


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: setup-workstation }

