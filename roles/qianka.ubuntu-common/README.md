ubuntu-common-role
==================


Requirements
------------

- Ubuntu Server 14.04 LTS
- Ansible 1.5+


Role Variables
--------------

- inventory_hostname_short
- locale
- timezone
- ubuntu_apt_mirror
- ubuntu_release_code


Dependencies
------------


Example Playbook
----------------

```yml
- hosts: servers
  vars:
    ubuntu_apt_mirror: http://mirrors.aliyuncs.com/ubuntu
  roles:
     - qianka.ubuntu-common
```

License
-------


Author Information
------------------
