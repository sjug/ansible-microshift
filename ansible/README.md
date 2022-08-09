# Install Microshift

## Prereqs

- Ansible
  - `ansible-galaxy collection install community.general`
  - `ansible-galaxy collection install community.crypto`
  - `ansible-galaxy collection install pbench.agent`

Note: ensure your ansible galaxy user directory is exported:
```
export ANSIBLE_ROLES_PATH=$HOME/.ansible/collections/ansible_collections/pbench/agent/roles:$ANSIBLE_ROLES_PATH
```
