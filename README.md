# privatebin-ansible

This will install a python cli for private bin. It will also prompt for values. Which will be templated in the file that will be attached to the privatebin request.

There is template file dev-lts.j2 put in your private information then you will need to encrypt it via the command 'ansible-vault encrypt dev-lts.j2' to keep it safe don't forget your vault password.

To run: 'ansible-playbook createlink.yml --ask-vault-pass'
