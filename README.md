ansible-awx-zimbra-single
=========================

This role is compatible with AWX and automates the process of installing single-server Zimbra Open Source Edition v8.8.15 on CentOS 8.

Requirements
------------

1) Must be a fresh CentOS 8 minimal installation
2) Static network configuration must be already set

Role Variables
--------------

Apply changes to suit your environment.

    zimbra_timezone: Asia/Manila
    zimbra_fqdn: mail.example.com
    zimbra_shortname: mail
    zimbra_network_name: enp1s0
    zimbra_ip: 192.168.122.75
    zimbra_reverse_ip: 122.168.192
    zimbra_ptr: 75
    zimbra_subnet: 192.168.122.0/24
    zimbra_forwarders: 8.8.8.8; 8.8.4.4;
    zimbra_domain: example.com
    zimbra_admin_password: ansible@zimbra2020
    zimbra_system_password: zimbra@ansible2020


License
-------

MIT License

Author Information
------------------

Author: Jan Cubillan<br/>
GitHub: https://github.com/jancubillan<br/>
