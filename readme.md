# Ansible Role: Chromedriver

Installs a specifiable version of Chromedriver on Debian based systems

## Role variables

    chromedriver_version: 2.29
    
Specify a specific version to install, will default to `latest`.

Will check storage.googleapis.com for the latest version string.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: mylaptop
      roles:
        - { role: rdeknijf.chromedriver }         

License
-------
MIT / BSD

Author Information
------------------
Rutger de Knijf
<rutger@deknijf.com>
