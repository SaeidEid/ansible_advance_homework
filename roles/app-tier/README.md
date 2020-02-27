Role Name
=========

Installs tomcat and deploys the backend application

Requirements
------------

No additional requirements needed. 

Role Variables
--------------

app_tier_tomcat_web_root: path to the webroot directory of tomcat

Dependencies
------------

No dependencies

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: app-tier }

