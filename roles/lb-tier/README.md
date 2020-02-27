Role Name
=========

lb-tier: installs hqproxy and configures load balancer

Requirements
------------

No requirements

Role Variables
--------------

_yum_packages: yum packages to be installed (haproxy in this case)

Dependencies
------------

No dependencies

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lb-tier }

