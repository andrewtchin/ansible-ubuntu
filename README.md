# ansible-ubuntu

## Playbooks

### Run locally

```
-c local -i inventory
```

### ubuntu.yml

Base
```
ansible-playbook -vvv playbooks/ubuntu-desktop.yml --ask-become-pass --extra-vars=@vars/ubuntu.json
```

Developer
```
ansible-playbook -vvv playbooks/developer.yml --ask-become-pass
```

Work
```
ansible-playbook -vvv playbooks/work-vmware.yml --ask-become-pass
```

Work Docker Fix
```
ansible-playbook -vvv playbooks/vmware-docker.yml --ask-sudo-pass
```


## Playbooks

### tiddlywiki
```
ansible-playbook -vvv playbooks/tiddlywiki.yml --ask-become-pass
```

### kvm-host
```
ansible-playbook -vvv playbooks/kvm-host.yml --ask-become-pass --extra-vars=@vars/kvm-host.json
```

### kvm-client
```
ansible-playbook -vvv playbooks/kvm-client.yml --ask-become-pass
```

### nut
```
ansible-playbook -vvv playbooks/nut.yml --ask-become-pass --extra-vars=@vars/nut.json
```

### ubuntu-webserver
```
ansible-playbook -vvv ubuntu-webserver.yml --ask-become-pass
```

## TODO
 - Generate new /etc/ssh/moduli
