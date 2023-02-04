# ansible-playbooks

A set of playbooks for ansible

## deploy-ossechids-ubuntu.yml

Deploy an OSSEC host-based intrusion detection system (HIDS) onto an Ubuntu 22.04 host.

This playbook assumes that the client key is stored at `/etc/ansible/files/ossec/client_keys/{{inventory_hostname}}`

There should also be a desired config file stored at `/etc/ansible/files/ossec/etc/ossec.conf`

## deploy-apache-ubuntu.yml

Deploy a simple apache webserver on an ubuntu host

Web server files should be stored at `/etc/ansible/files/apache/`


## deply-nginx-ubuntu.yml

Deploy a simple nginx load balancer on an ubuntu host

Web server configs should be stored at `/etc/ansible/files/nginx/`
