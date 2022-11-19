# ansible-playbooks
ansible-playbook examples and use cases

### Playbooks
- playbooks/ping.yml - ping localhost and do not gather facts

Example: `ansible-playbook playbooks/ping.yml`

- playbooks/update.yml - update debian based localhost and using elevate privledges

Example: `ansible-playbook playbooks/update.yml --ask-become`