# Ansible Playbooks

## Install Ansible

```
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
```

## Install Roles

```
ansible-galaxy install -r requirements.yml
```

## Command

```
ansible-playbook --ask-become-pass -i localhost, main.yaml --connection=local
```
