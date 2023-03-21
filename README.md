# Ansible

I would be updating this repository as I learn more on Automation with Ansible.

Ansible is one amazing configuration management and provisioning utility that enables you to automate a whole lot of things, Making I.T processes seamless.

# * List all servers/hosts/nodes

ansible all --list-hosts

# * Pull basically all information about a server

ansible all -m gather_facts

# * Make a connection to each host within the inventory

ansible all --key-file ~/.ssh/ansible -i inventory -m ping

# * create an ansible config file, add default rules/paths 
ansible all -m ping

# * Ping/target a particular node
ansible -i inventory db_servers -m ping

# * Ansible Modules
Ansible modules are packages,units,bits, library, that ansible is built around to interact with other target machines or nodes.
Or they can be said to be units of code that can be used to control system resources or to execute system commands

ansible-doc -l 
