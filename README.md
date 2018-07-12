# ansible-ubuntu

## Playbooks

### Run locally

```
--connection local --inventory `localhost,`
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

### ubuntu-browsing

```
ansible-playbook -vvv ubuntu-browsing.yml --inventory inventory --ask-become-pass
ansible-playbook -vvv ubuntu-browsing.yml --inventory 'localhost,' --connection local --ask-become-pass
```

## TODO
 - Generate new /etc/ssh/moduli
