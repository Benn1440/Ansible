# Ansible

I would be updating this repository as I learn more on Automation with Ansible.


#Make a connection to each host within the inventory

 ansible all --key-file ~/.ssh/ansible -i inventory -m ping
