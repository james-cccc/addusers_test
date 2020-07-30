addusers_test
=========

This role was created to showcase the testing of Ansible roles with Molecule using CI with GitHub actions

![CI](https://github.com/james-cccc/addusers_test/workflows/CI/badge.svg)

Dependencies
------------

If you re to perform testing locally you need the following installed:

* yamllint
* ansible-lint
* molecule
* podman 


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
---
- hosts: servers
  remote_user: root
  roles:
    - addusers_test
```

License
-------

BSD

