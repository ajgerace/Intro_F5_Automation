# Intro_F5_Automation

## Introduction
This repository contains a group of labs that will introduce basic Ansible concepts. These labs will introduce these concepts and apply them to typical F5 tasks such as creating nodes, pools and virtual servers.  

Ansible utilizes the YAML markup language.  YAML uses spaces for indentation.

Released F5 Ansible module documentation can be [here](http://docs.ansible.com/ansible/latest/list_of_network_modules.html#f5).

### Some useful links 
[YAML lint](http://www.yamllint.com/) - Validate your YAML 
[YAML Tutorial](https://gettaurus.org/docs/YAMLTutorial/) 


### Lab1 - Creating a node 

### Lab2 - Internal variables
The user will utilize variables defined with-in the playbook to be used with bigip_node ansible module.  This lab will delete a node based on the state 

### Lab3 - Loops
Utilize with_items to create an item with multiple input items. In this lab we will utilize with_items to add multiple nodes with-in a single task.

### Lab4 - Vault
Ansible Vault is an ansible feature that allows sensitive data such as user credentials to be encrypted. Variables can be encrypted in place and decryption will happen at runtime.  The vault password can be passed as an argument 

### Lab 5 - Creating an application stack
This lab will utilize the bigip_node, bigip_pool, bigip_pool_members, bigip_irule and bigip_virtual_server modules.

### Lab 6 - Creating application stack using declarative iApp interface
