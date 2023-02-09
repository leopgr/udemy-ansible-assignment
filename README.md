# Udemy Ansible Assignment

This is a solution for the Ansible Assignment on Udemy https://www.udemy.com/learn-ansible-advanced

This assignment tests the students knowledge on deploying a distributed web application on cloud using fully automated Ansible playbooks. The solution is shared to the instructor and student community using github repository and feedback will be given.

## Solution

### Infrastructure 
 
It were created local VM using VirtualBox.
- 1 DB server
- 2 Web Servers
- 1 Ansible Controller

### Ansible Project

It were created roles do deploy MySQL, Python and Flask
- **Roles:** ansible-role-mysql: A role to install and configure MySQL on any given systems
- **Roles:** ansible-role-flask: A role to install and configure Flask application on multiple 
- **Roles:** ansible-role-python: A role to install Python and its dependencies for this project 

Group Variables to have following properties:

- **db_name:** Database name
- **db_user:** Database user to create
- **db_password:** Password for the Database user
- **db_name:** Database name
- **db_user:** Database user
- **db_user_password:** Database user password
