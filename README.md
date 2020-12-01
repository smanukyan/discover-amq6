# Discover AMQ Broker v6

Ansible script to look for a Red Hat AMQ Broker v6 installations on RHEL.
The script will look for the essential file 'activemq.xml' starting from the root folder.

## Prerequisites

Ansible must be installed on client wher the script will be run.

## Usage

1. define your target servers in the hosts file  
2. Run `ansible-playbook main.yml -i hosts`
