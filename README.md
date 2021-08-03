# Ansible.Observium.Update

This project is for updating the Observium server and pollers.

It has 3 main files:

- inventory file
  <br>This file is where we define our Observium servers,some variables.
- /group_vars/servers file
  <br>This file hosts the svn user/password and the sudo password
- main.yml file
  <br>This file consists of 3 tasks. One to check the svn status of the updates,
  <br>one to do svn update and the last one that is run only on the master server, the DB update
