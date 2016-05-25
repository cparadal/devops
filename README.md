# devops

This (pretty rough) Ansible playbook deploys a dockerized working MongoDB shard (localhost), with a replica set consisting of 3 different nodes. 
It *should* be amended in order to make use of the docker module instead of relying on the command & shell modules for calling docker commands. That would bring advantages such as idempotence.

- This Ansible playbook assumes that  there is a working Docker environment running on the system where it's going to be deployed and that the mongo client is installed on that host system.
- Run the playbook using sudo, as stated below.
# ansible-playbook playbooks/devops.yml -s

