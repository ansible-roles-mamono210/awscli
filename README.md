[![](https://github.com/ansible-roles-matsumura/awscli/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/awscli/actions?query=workflow%3Ayamllint)
[![](https://github.com/ansible-roles-matsumura/awscli/workflows/molecule/badge.svg)](https://github.com/ansible-roles-matsumura/awscli/actions?query=workflow%3Amolecule)
[![](https://github.com/ansible-roles-matsumura/awscli/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/awscli/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/awscli/workflows/Trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/awscli/actions?query=workflow%3A%22Trailing+whitespace%22)

Role Description
=========

Installs [AWS CLI version2](https://docs.aws.amazon.com/cli/index.html) for CentOS7/CentOS8.

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
