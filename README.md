## ansible-druid

An ansible role to install and configure druid.

## Variables path
- roles/default/main.yml
- roles/vars/main.yml
- inventory/group_vars/*

## Inventory path
- inventory/hosts.ini

## Run command
ansible-playbook -i inventory/hosts.ini -b druid.yml -vv
