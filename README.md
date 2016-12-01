# Ansible playbooks for my personal Ubuntu


See available tasks

    ansible-playbook master.yml --list-tags

Run all tasks

    ansible-playbook master.yml

Run single task

    ansible-playbook master.yml --ask-sudo-pass --tags npm_global_modules
