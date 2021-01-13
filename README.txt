Create keypairs for the root user:
# ssh-keygen -t rsa  
without passphrase, put line from the id_rsa.pub to authorized_keys
# cat id_rsa.pub > authorized_keys

Run playbook
# ansible-playbook -i inventory playbook
