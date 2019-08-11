This playbook installs AWS CLI on CentOS7.

## Install AWS CLI

Change to root and execute commands below.

```
ansible-galaxy install -r roles/requirements.yml
ansible-playbook -i localhost, -c local install.yml
```


