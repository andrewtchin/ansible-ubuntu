# ansible-ubuntu

## Playbooks

### ubuntu.yml

Base
```
ansible-playbook -vvv playbooks/ubuntu-desktop.yml --ask-sudo-pass --extra-vars=@vars/ubuntu.json
```

Developer
```
ansible-playbook -vvv playbooks/developer.yml --ask-sudo-pass
```

## Playbooks

### TiddlyWiki
```
ansible-playbook -vvv playbooks/tiddlywiki.yml --ask-sudo-pass
```

### TODO
 - Generate new /etc/ssh/moduli
