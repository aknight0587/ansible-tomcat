A collection of roles and playbooks that I've written for Ansible which also includes a Vagrantfile that can be used to test functionality of the code in Vagrant. Right now this code is written to work on RedHat/CentOS systems. Adding support for Ubuntu/Debian is on my to-do list.

Breif description of each role:

Tomcat - Installs a version of Tomcat that is specified in common.yml and creates a symlink that is specified in common.yml

Java - Install a version of Java that is specified in common.yml. It is using openJDK, which should be 

Vagrantfile is using CentOS 6.8
