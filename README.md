Run the playbook:

  sudo ansible-playbook provision.yml -i hosts --vault-password-file=./vault_pass.txt

Edit the vars.yml file:

  ansible-vault edit --vault-password-file=./vault_pass.txt vars.yml

# Ubuntu 14.04
`unity-tweak-tools` can tune the number of desktops in Unity.

