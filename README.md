# rdmotd 

This is a simple MOTD install automation project with Ansible

## User Inputs
User may pass extra argument as below:
ansible-playbook site.yml --extra-vars="{ 'messages': [ "Welcome", "Good Day" ] }"
