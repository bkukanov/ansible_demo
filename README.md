ansible_demo
================

Ansible playbook for control AWS EC2 / Google Compute Emgine instances.

About Ansible playbooks: http://www.ansibleworks.com/docs/playbooks.html

List of playbooks:
----------------
launch-demo-instances.yml - create new instances on aws ec2 
(e.g. `ansible-playbook -i hosts_zones launch-demo-instances.yml`)

subutai-install.yml - install Subutai Social on aws ec2 / gce instances 
(e.g. `ansible-playbook -i hosts_ec2 subutai-install.yml`)

authorized_key.yml - add local ssh-key on remote instance 
(e.g. `ansible-playbook -i hosts_gce authorized_key.yml`)
