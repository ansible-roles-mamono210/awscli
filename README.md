[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/awscli/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/awscli/tree/main)

Role Description
=========

Installs [AWS CLI version2](https://docs.aws.amazon.com/cli/index.html) for CentOS Stream 9.

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
