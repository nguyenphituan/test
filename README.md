Ansible playbook to add public key in server

To remove user, use this command:
ansible target -m user -i hosts -a 'name=username state=absent' --sudo
