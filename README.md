# ansible-glpi-mysql

This is an ansible configuration for the Gestionnaire Libre de Parc Informatique (GLPI) which is well-known open source for IT Asset Management, issue tracking system and service desk system. This software is written in PHP and distributed as open-source software under the GNU General Public License. 

This configuration  has parameters and suggests the use of MySQL database, however this can be easily modified to use another database.

Prerequisites
-----------------------

Ansible

    sudo apt-get install ansible


Installation && Running
-----------------------

Do a git clone of the project:

	git clone https://github.com/dcc6fvo/ansible-glpi-mysql


Access the newly created folder with the git clone command and type the following command:

    ansible-playbook provisioning.yml -i hosts

 
 **IMPORTANT!Your SSL key's must be placed in the folder: '/var/ansible/ssl'. You can change the this folder and other parameters accessing the file group_vars/all.yml** 

