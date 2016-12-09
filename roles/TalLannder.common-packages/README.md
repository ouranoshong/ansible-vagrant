# common-packages

Ansible role to install common packages from a variable list defined in group_vars or host_vars.

The role can be included on the top play for "all" hosts since it won't install
any packages unless the variable packages is defined.


##Role Variables

packages

```
packages:
 - name: foo
   update_cache: yes
 - name: bar
   state: absent
 - name: nginx
   default_release: squeeze-backports
   

```


##Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: servers
  roles:
   - common-packages
```


##License

MIT


##Author Information

Tal Lannder
tal@pjili.com
