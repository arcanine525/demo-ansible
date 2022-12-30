# Sample ansible

## Sample cmd:
ansible-playbook -i <host_file>  <playbook_file.yml>


## When fail to authentication add option to cmd like this:
ansible-playbook --become --ask-become-pass -i horus-global  docker/ubuntu.yml
