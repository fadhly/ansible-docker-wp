# ansible-docker-wp
Ansible Script for Running Wordpress on Docker Automatically

Method: <br />
1. Installing Password Generator on Ansible Host
2. Create Random Password on Ansible Host
3. Installing Docker on Remote Host (Server)
4. Pull Docker Image on Remote Host (Server)
5. Create Wordpress and Mysql Container
6. Running the container and publish ports
7. Access Remote Host with Browsers and Setup WP

Usage: <br />
ansible-playboook -i inventory ansible-docker-wp.yml

Note: <br />
Modify your /etc/hosts and add your server+ip <br />
Modify your 'ansible_user' on ansible-docker-wp.yml 

Videos: <br />
https://youtu.be/dhubl6uNb8Q

