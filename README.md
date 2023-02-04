##
ansible all --key-file ~/.ssh/id_rsa -i inventory -m ping -u ec2-user

### run the ansible playbook
ansible-playbook deploy-techmax.yml