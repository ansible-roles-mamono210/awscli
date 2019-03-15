This playbook installs AWS CLI on CentOS7.

## Install AWS CLI

Change to root and execute commands below.

```
ansible-galaxy install -r requirements.yml
ansible-playbook -i localhost, -c local install.yml
```


