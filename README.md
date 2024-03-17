To prep clean pie OS

ansible-playbook --ask-become-pass bootstrap.yml

To install everything else, after initial prep

ansible-playbook main.yml
