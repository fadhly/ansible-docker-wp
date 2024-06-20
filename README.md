# ansible-docker-wp
Ansible Script for Running Wordpress on Docker Automatically

Method: 
1. Installing Password Generator on Ansible Host
2. Create Random Password on Ansible Host
3. Installing Docker on Remote Host (Server)
4. Pull Docker Image on Remote Host (Server)
5. Create Wordpress and Mysql Container
6. Running the container and publish ports

Usage:
ansible-playboook -i inventory ansible-docker-wp.yml

Note:
Modify your /etc/hosts and add your server+ip
