
# Custom Ansible-Playbooks

Steps to run these playbooks

1. Install ansible on the host computer. For information on how to install it on your OS please check this guide : [Ansible Installation](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
2. Clone the project
3. Create 
4. Go to required stack's folder (currently node or laravel) 
5. Copy the hosts.example file to hosts file and add the IP address and ssh details of the server(s) on which you want to run the script on.
6. Run the following command :
ansible-playbook -i ../hosts  < yaml file inside the stack > 