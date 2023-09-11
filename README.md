# 272-ansible-assignment

Create 3 Virtual Machines
Using Ansible on VM1, Deploy Web Servers on VM2 and VM3 to display "Hello World from SJSU-X" where X is the ID of the virtual machine.
Also, provide a way to un-deploy the web server on both VMs through Ansible

Playbook to install deploy and start the web servers on VM2 and VM3: webserver.yml
Host file for IP: inventory.ini
Command to execute the playbook: ansible-playbook -i inventory.ini webserver.yml

Playbook to un-deploy the webservers: undeploy-webserver.iml
Command to execute the playbook: ansible-playbook -i inventory.ini undeploy-webserver.yml


