= Discover AMQ Broker v6

Ansible script to look for a Red Hat AMQ Broker v6 installations.
The script will look for the essential file 'activemq.xml' starting from the root folder.

== Prerequisites

Ansible

== Usage

1. define your target servers in the hosts file  
2. ansible-playbook main.yml -i hosts
