# CLO5

## How to access to secrets
(password: test)
```bash
ansible-vault edit group_vars/all/vault.yml
```

## How add ssh key for accessing vms
```bash
eval `ssh-agent`
ssh-add ssh_keys/test_clo5
```


## How to run the playbook
(password: test)
```bash
ansible-playbook playbook.yml --ask-vault-pass
```
