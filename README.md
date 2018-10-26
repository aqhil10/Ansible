# Ansible
# attempt to install cPanel on 6 server
# I have performed package update on all server and set the host name
# created a new ansible server and added the 6 IP address in the host file of ansible server
# generated ssh key and copied the same to the 6 client servers

# Then created a cpanel.yaml file on ansible server

ansible-playbook cpanel.yaml --syntax-check
ansible-playbook cpanel.yaml
