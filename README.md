# simple-ansible-playbooks
Create and manage a simple docker-linux based hosts using ansible


## What this project does?

This project is all about using ansible to create and manage environment for a multilayered web application.
It contains scipts that takes care of deploying, running and maintaing the complete tech stack of a Flask based web application.

The web-applicaiton consists of following :

[control] - Ansible is installed on this instance/machine and acts as master

[loadbalancer] - NGINX Loadbalancer for the webservers

[database] - MySQL database instance is spinned up and configured

[webservers] - 2 Apache webservers
