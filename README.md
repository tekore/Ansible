![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white)

# Ansible Automation

Variable Ansible playbooks I use for Automation

## Table of Contents
- [Usage](#usage)
- [Maintainers](#maintainers)

## Usage
- Clone the repo:
```sh
$ git clone https://github.com/tekore/Ansible
```

- Run a playbook in push mode:
```sh
$ ansible-playbook <PLAYBOOK>.yml
```
- Run a playbook in pull mode:
```sh
$ ansible-pull -U https://github.com/tekore/Ansible.git roles/microk8s/mk8s.yml
```

## Maintainers
[@Tekore](https://github.com/tekore)