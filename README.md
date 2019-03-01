This repo for exercise 1 and 2

I use Ansible for automation tools

Setup to my cloud server on Digital Ocean. 

OS: Ubuntu 16.04

Exc1: Setup with role clitools, createAccount, updateDNS
Exc2: Setup with role mysql, nginx, php, phpmyadmin


Just change "roles" field in playbook.yml to chose the components you want to install


Update ansible hosts file to change the production server info

Run playbook with command 

```bash
ansible-playbook playbook.yml -vvvv
```