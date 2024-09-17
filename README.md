# BobsPlaybooks
Useful Ansible playbooks

Before Ansible will work properly you will need to make sure: 

1. All hosts are assigned an IP address and are reachable from the system that has Ansible installed
2. SSH is installed, enabled and running on all hosts
- You will want to decide if you are going to enforce key-based authentication. If you don't you will need to make some changes to your playbooks.

You may run the playbooks using this command: 

```ansible-playbook -i inventory_file_name playbook_name.yml```
