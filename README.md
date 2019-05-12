# ansible-roles
httpd
A brief description of the role goes here.

Requirements
None

Role Variables
Variable is coming from vars/main.yml

dest: "/var/www/html"
Dependencies
None

Example Playbook
---
- name: Installing httpd
  hosts: webservers
  become: true
  roles:
    - httpd
