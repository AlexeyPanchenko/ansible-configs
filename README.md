# ansible-configs

### Configure project

----
* `ansible-galaxy install -r requirements.yml` (install requirements for ansible config)
* add ssh key to root directory as file .ssh_key

### Run with

----
```shell
ansible-playbook -i inventory jenkins-master-state.yml
```