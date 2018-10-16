My server setup using Ansible and Docker
=========================================

A setup for for my servers. 
At the moment I'm playing around so don't
expect anything working in here.

The stuff you find is mainly influenced (aka taken)
from this [blog post](https://ejosh.co/de/2015/05/ansible-for-server-provisioning/)
by Joshua Johanan and the corresponding [github repo](https://github.com/johanan/Ansible-and-Docker).

### Setup a new host

To setup a complete new host, the basic playbook can be used.
It installs a new user, a firewall and configures ssh connection.

`ansible-playbook basic.yaml --vault-password-file ~/.vault_pass.txt -k -l <hostname>`



