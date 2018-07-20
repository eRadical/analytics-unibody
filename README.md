analytics-unibody
=================

Ansible role that sets up a farm of analytics collectors based on nginx

Requirements
------------

On the target machine: EPEL repo already installed

Role Variables
--------------

unibody_nginx_version - the version of nginx that will be downloaded and compiled


Example Playbook
----------------

To add to a server simply add the role:

    - hosts: servers
      roles:
         - eRadical.analytics-unibody

All variables used in defaults folder are prefixed with "unibody_" so you can use overrides in your environment.

License
-------

GNU General Public License v3.0

Author Information
------------------

Gabriel PREDA
Twitter: eRadical
