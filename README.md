# Ansible

Ansible scripts to provision VM.

## Provision Users

Run `ansible-playbook -i hosts.yml user-provisionning.yml -u debian` to add the SSH-keys.
Run `ansible-playbook -i hosts.yml install.yml -u debian` to install go.

You may run `ANSIBLE_COW_SELECTION=random ansible-playbook -i hosts.yml install.yml -u debian` if you like a bit of fun ;).

## Notes

The go install role is adapted from https://github.com/jlund/ansible-go.
