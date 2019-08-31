# Ansible playbook for Ubuntu workstation

This project contains the Ansible playbook for my Ubuntu workstation.

## Install Ansible

```bash
sudo apt update
sudo apt install software-properties-common
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```

## Run the playbook

Full reference for `ansible-playbook` command is available at https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html.

```bash
git clone https://github.com/nicola88/ansible-workstation-ubuntu.git
cd ansible-workstation-ubuntu
# Ask before executing each step and show detailed output
sudo ansible-playbook --step -v local.yml
```