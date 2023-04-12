This repository accompanies my answer to <https://stackoverflow.com/questions/75991358/ansible-roles-and-vars-vault-yml-file>.

The vault password is `secret`, but you won't need to type it in because the included `ansible.cfg` sets `vault_password_file` to a file containing the secret.
