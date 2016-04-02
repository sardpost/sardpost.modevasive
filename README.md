Role Name: sardpost.modevasive
=========

Ansible role for installing mod_evasive in Apache on EL 7 platform (RHEL/Centos 7).
It checks if Epel repository is installed and installs Apache Httpd if not already present.

Requirements
------------

Platform: RHEL/Centos 7


Dependencies
------------
This role needs one role:

  - geerlingguy.apache


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  - name: Install Modevasive
    hosts: webserver
    remote_user: centos
    sudo: yes

    roles:
      - sardpost.modevasive

Version:
--------
0.1

License
-------

GPLv3+

Author Information
------------------

Davide M. Puggioni
