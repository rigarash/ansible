# ansible
My personal ansible playbooks

## How to use
After installing ansible, run playbook as follows:

```Shell
ansible-playbook site.yml --inventory-file=hosts --limit=localhost[,server] --ask-become-pass
```
