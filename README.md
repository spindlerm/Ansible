To prep clean pie OS, override all settings in the ansible.cfg

Note:

The --user is the admin account created during inital setup of the pie


ansible-playbook --user admin --ask-pass --become-user root  --ask-become-pass bootstrap.yml


To install everything else, after initial prep

ansible-playbook main.yml
