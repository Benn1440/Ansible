# Ansible

I would be updating this repository as I learn more on Automation with Ansible.

# * List all servers/hosts/nodes

ansible all --list-hosts

# * Pull basically all information about a server

ansible all -m gather_facts

# * Make a connection to each host within the inventory

ansible all --key-file ~/.ssh/ansible -i inventory -m ping

# * create an ansible config file, add default rules/paths 
ansible all -m ping
