[![](https://github.com/ansible-roles-matsumura/awscli/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/awscli/actions?query=workflow%3Abuild)

Role Description
=========

Installs [AWS CLI version2](https://docs.aws.amazon.com/cli/index.html) for CentOS7/Stream8.

Requirements
------------

None

Role Variables
--------------

```YAML
awscli_working_dir: /tmp/awscli_working_dir
```

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - awscli
```

License
-------

BSD
