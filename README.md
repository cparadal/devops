# devops

This (pretty rough) Ansible playbook deploys a dockerized working MongoDB shard, with a replica set consisting of 3 different nodes. 
It *should* be amended in order to make use of the docker module instead of relying on the command & shell modules.

- This Ansible playbook assumes there is a working Docker environment running on the system where it's going to be deployed.
- Run the playbook using sudo, as stated below.
# ansible-playbook playbooks/devops.yml -s

