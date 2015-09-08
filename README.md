# ansible-ubuntu

## Playbooks

### ubuntu.yml

* ansible-playbook -vvv playbooks/ubuntu.yml --ask-sudo-pass --extra-vars=@vars/deploy_vars.json

For local install
* ansible-playbook -vvv playbooks/ubuntu-local.yml --ask-sudo-pass
  --extra-vars=@vars/ubuntu-local.json

## Roles
