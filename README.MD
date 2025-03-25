# learn ansible

ansible is developed using python.
to install ansible on linux, we use a python package manager called pip

ansible -i inventoryFileName all -e ansible_user=ec2-user -e ansible_password=DevOps321 -m ansible.builtin.ping