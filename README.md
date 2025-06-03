# Ansible Project: Web Server & User Setup

This Ansible project automates the deployment of a basic Apache web server and user creation.

## Features

- Installs and enables Apache
- Creates predefined users with Bash shell
- Adds users to the sudo group

## Structure

- `inventory.ini`: Target hosts
- `site.yml`: Main playbook
- `roles/`: Modular tasks for `webserver` and `users`

## Run the playbook

```bash
ansible-playbook -i inventory.ini site.yml
```

##  Usage Instructions

Install Ansible (on control machine):
```bash
sudo apt install ansible
```

## Run the playbook:
```bash
ansible-playbook -i inventory.ini site.yml
```
