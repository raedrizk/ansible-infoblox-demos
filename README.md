# ansible-infoblox-demos

Ansible collection (`rsoliman.infoblox_demos`) containing some roles to demonstrate using ansible to automate Infoblox tasks, as well as sample playbooks that call on those roles. 

Playbooks included in this repo:
- infoblox_get_next_ip

The `rsoliman.infoblox_demos` collection has a dependancy on the modules from the `infoblox.nios_modules` collection.

To use the playbooks in Ansible Controller:
1. create a new project pointing to this repo
2. define a custom credential type to represent Infoblox
3. create job templates to use the playbooks you need
