# ansible-ubuntu

## Playbooks

### ubuntu.yml

Base
```
ansible-playbook -vvv playbooks/ubuntu.yml --ask-sudo-pass --extra-vars=@vars/ubuntu.json
```

Developer
```
ansible-playbook -vvv playbooks/developer.yml --ask-sudo-pass
```

## Roles
