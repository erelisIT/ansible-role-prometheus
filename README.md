Role Name
=========

Ansible role for installing and configuring Prometheus Server.

Requirements
------------

n/a

Role Variables
--------------

todo

Dependencies
------------

- role: 

Example Playbook
----------------

The example of how to use the role in the playbook:

    - hosts: prometheus
      become: yes
      vars_files:
        - vars_prometheus_server.yml
      
      roles:
         - { role: firewalld-prometheus-server }
         - { role: prometheus }

