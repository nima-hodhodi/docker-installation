# dokcer-installation
with this ansible playbook you can install docker and docker compose and ... in your remote servers.

just set ip address (or ip addresses) for your server (servers) in inventory.ini and set the path of ssh private key and run below command :
ansible-playbook -i inventory.ini --become --become-user=root  -vv install_docker.yaml
