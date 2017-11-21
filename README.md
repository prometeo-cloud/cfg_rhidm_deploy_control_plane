ansible-galaxy install -r requirements.yml -p ./roles
ansible-playbook -i inventory site.yml --extra-vars "host_type=docker"
