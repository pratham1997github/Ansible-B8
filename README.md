Configuration Management Tool:
WHAT
Terraform | Ansible
Infra Provisioning tool | Configuration Management tool
WHY
Manualy - 100servers (timeconsume, human-error) (10 command)
Shell Script - (server manage) - (4 command)
Conf Mgmt tool
Ansible | Puppet | Chef
Push Based mech | Pull based mech
Python | Rubby DSL
SSH Connection | Agents Deployed on server
HOW
Install Ansible

Modules - python

syntax: ansible -i hosts all -u --private-key= -m

ansible-playbooks (yaml)

Syntax to generate config file: ansible-config init --disable > ansible.cfg

Syntax to play the playbook: ansible-playbook -u ubuntu --private-key=idrsa playbook.yaml

yaml - indentation specific

ansible-playbook -e URL=cli.cloudblitz.in -u ubuntu --private-key=../id_rsa 2.\ variables. yaml

ansible-oncdec-b8/README.md at main · shubhamkalsait/ansible-oncdec-b8# Ansible-B8
