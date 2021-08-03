# Ansible.Observium.Update

It has 3 main files:

- inventory file
  This file is where we define our Observium servers some variables.
- /group_vars/servers file
  This file hosts the svn user/password and the sudo password
- main.yml file
  This file consists of 3 tasks. One to check the svn status of the updates,
  one to do svn update and the last one that is run only on the master server, the DB update
