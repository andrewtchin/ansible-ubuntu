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

### tiddlywiki
```
ansible-playbook -vvv playbooks/tiddlywiki.yml --ask-sudo-pass
```

### kvm-host
```
ansible-playbook -vvv playbooks/kvm-host.yml --ask-sudo-pass --extra-vars=@vars/kvm-host.json
```

### kvm-client
```
ansible-playbook -vvv playbooks/kvm-client.yml --ask-sudo-pass
```

### nut
```
ansible-playbook -vvv playbooks/nut.yml --ask-sudo-pass --extra-vars=@vars/nut.json
```

### cozy
```
ansible-playbook -vvv playbooks/cozy.yml --ask-sudo-pass
```

## TODO
 - Generate new /etc/ssh/moduli
