# ansible-configs

### Configure project

----
* `ansible-galaxy install -r requirements.yml` (install requirements for ansible config)
* add file .ssh_jenkins_master_private_key_path with path to your private key
* add file .ssh_jenkins_agent_public_key_path with path to agent public key

### Run with

----
```shell
ansible-playbook -i inventory jenkins-master-state.yml
ansible-playbook -i inventory jenkins-agent-state.yml
```