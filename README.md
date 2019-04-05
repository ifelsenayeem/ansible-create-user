# Ansible for adding a new user in ubuntu as sudoers

Ansible is an IT automation tool. It can configure systems, deploy software, and orchestrate more advanced IT tasks such as continuous deployments or zero downtime rolling updates.

This [link](https://docs.ansible.com/) helps you to do other setup like installation and all.

## Run
```
git clone https://github.com/ifelsenayeem/ansible-create-user.git

cd ansible-create-user

ansible-playbook -i hosts/dev -e "@config/dev.json" user.yml
```
Note: Change username, password, ansible_host and ansible_user in the playbook.
