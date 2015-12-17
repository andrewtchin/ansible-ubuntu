# ansible-ubuntu

## Playbooks

### ubuntu.yml

Base
```
ansible-playbook -vvv playbooks/ubuntu.yml --ask-sudo-pass --extra-vars=@vars/deploy_vars.json
```

Developer
```
ansible-playbook -vvv playbooks/developer.yml --ask-sudo-pass
```

## Roles
