# ansible-docker-ucp

Ansible playbook to deploy Docker EE Engine and UCP

Requires Ansible 2+ setup: 

1: Install ansible 2+ on the control node: https://docs.ansible.com/ansible/2.5/installation_guide/intro_installation.html
2: ssh-key based authentication is required by the ansible control node to communicate with worker nodes: 
https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/6/html/deployment_guide/s2-ssh-configuration-keypairs

For UCP, you need to copy your license file to ./files and run `ansible-playbook ucp-docker-deploy.yml`


