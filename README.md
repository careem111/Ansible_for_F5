# Ansible_for_F5

By using this script we can extract details from F5

Requirements

Ansible
Python pip
netaddr
suds

Install

apt-get install software-properties-common
apt-add-repository ppa:ansible/ansible
apt-get install ansible version==2.0

pip install f5-sdk
pip install netaddr

pip install suds
pip install suds bigsuds

How to use

1. Create a file called hosts and add the IP 
  
    [bigip]
    10.96.0.15
    
2. Execute the command after writing the playbook

    ansible-playbook -i hosts playbook.yaml

