Ansible role: SVN
========

An Ansible Role that installs Subversion on RedHat/CentOS

Requirements
------------

None

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

cm_prefix: "/var/CM"

This is the overall directory for  the projects

cm_project: "default"

This is the "default" project name

cm_admin_user: admin

Default admin user

cm_admin_pw: admin

Default admin user password


Dependencies
------------

geerlingguy.apache

Example Playbook
-------------------------

  roles:
  - geerlingguy.apache
  - jermon.svn


License
-------

GPL

Author Information
------------------

This role was created in 2014 by Jerker Montelius


