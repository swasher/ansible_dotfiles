# ansible_dotfiles
My dotfiles and initial settings managed by Ansible

USAGE:

For manage remote host:

    ansible-playbook -i '10.254.3.133,' site.yml

For manage local host:

    ansible-playbook -i 'localhost,' --connection=local site.yml