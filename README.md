Run the playbook:

  sudo ansible-playbook provision.yml -i hosts --vault-password-file=./vault_pass.txt

Edit the vars.yml file:

  ansible-vault edit --vault-password-file=./vault_pass.txt vars.yml

