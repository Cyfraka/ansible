## Ansible ThinkPad X230
Ansible configuration for my ThinkPad X230 

## Work in progress!
This playbook is working but is under development.
The idea behind it is to be used as replacement my previus "dot files bare repository".

## What it does?
By this playbook I am able to manage installed application and config/dot files to multiple mashines and VM's at the same time.
After the initial ansible-pull command the playbok is creating a user and cron job to autoupdate if this repository is updated.

## How to use it?
> sudo pacman -S ansible git 

> sudo ansible-pull -U https://github.com/Cyfraka/x230-ansible.git
