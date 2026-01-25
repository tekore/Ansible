![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white)

# Ansible Automation

Variable Ansible playbooks I use for Automation

## Table of Contents
- [Usage](#usage)
- [Maintainers](#maintainers)

## Usage
- Clone the repo:
```sh
git clone https://github.com/tekore/Ansible
```

- Run a playbook in push mode:
```sh
ansible-playbook <PLAYBOOK>.yml
```
- Run a playbook in pull mode:
```sh
ansible-pull -U https://github.com/tekore/Ansible.git -i localhost, playbooks/provisionNewServer.yml
```

- Run a playbook in pull mode using your own custom variables:
```sh
ansible-pull -U https://github.com/tekore/Ansible.git -i localhost, playbooks/provisionNewServer.yml --extra-vars "@path/to/your_vars_file.yml"
```

#### Web interface access of services set up by these playbooks can be achieved via SSH tunnels like below
```sh
ssh -L 8443:localhost:8443 <USER>@<SERVER_IP> -p <SSH_PORT>
```

## Maintainers
[@Tekore](https://github.com/tekore)