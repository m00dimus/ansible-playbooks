# ansible-playbooks
ansible-playbook examples and use cases

### Playbooks
- ping.yml - ping localhost and do not gather facts

Example: `ansible-playbook ping.yml`

- update.vml - update debian based localhost and using elevate privledges

Example: `ansible-playbook update.yml --ask-become`