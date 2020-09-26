Role Name
=========

Configure basic settings, tools, and variables for a centos server

Requirements
------------

None

Role Variables
--------------

Optional Defaults:

  - centos_timezone: "Europe/Vienna" # default variable
  - centos_hostname: "{{inventory_hostname}}" # set hostname according to invetory file)

Mandatory Vars:

  - centos_ntp_server: ntp server from secret
  - centos_http_proxy: http proxy (protocol://host:port) from secret
  - centos_https_proxy: https proxy (protocol://host:port) from secret


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - centos_server

License
-------

GNU

Author Information
------------------

lhintzsc@cisco.com
