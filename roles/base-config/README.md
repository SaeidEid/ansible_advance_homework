Role Name
=========

base-config: Applies basic configuration for the host such as configuring yum repo

Requirements
------------

No requirements

Role Variables
--------------

base_config_configure_yum: Enables or disable configuring yum repo, true by default

Dependencies
------------

No dependecies

Example Playbook
----------------
    - hosts: servers
      roles:
         - { role: base-config, base_config_configure_yum: true }
