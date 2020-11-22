ansible-awx-zimbra-single
=========================

This role is compatible with AWX and automates the process of installing single-server Zimbra Open Source Edition v8.8.15 on CentOS 8.

Requirements
------------

1) Must be a fresh CentOS 8 minimal installation
2) Ansible AWX node must have the "netaddr" Python module installed

Role Variables
--------------

Apply changes to suit your environment.

    zimbra_timezone: Asia/Singapore
    zimbra_fqdn: mail.example.com
    zimbra_admin_password: ansible@zimbra2020

Inventory
---------

Inventory file similar below:

    [zimbra]
    192.168.122.75

License
-------

MIT License

Author Information
------------------

Author: Jan Cubillan<br/>
GitHub: https://github.com/jancubillan<br/>
