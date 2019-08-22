# ansible
My personal ansible playbooks

## How to use
After installing ansible, run playbook as follows:

```Shell
ansible-playbook site.yml --inventory=hosts.yml --limit=localhost[,server] --ask-become-pass
```
or for setting up windows:
```Shell
ansible-playbook site.yml --inventory=hosts.yml --limit=windows --ask-pass
```
