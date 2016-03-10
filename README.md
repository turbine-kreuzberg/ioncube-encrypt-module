Role Name
=========

encrypt listed directories with ioncube encoder

Requirements
------------

ioncube_encoder

Role Variables
--------------

```
php_version: 56
cpu_architecture: x86-64

directories_to_encrypt:
  - files/test
```


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: votum.ioncube-encrypt-module }


