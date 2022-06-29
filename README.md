# Configuration-Management-Automatio-with-Ansible

![Picture1](https://user-images.githubusercontent.com/50281621/176496822-96ebd976-09f3-46cb-90f4-bea2a2b513e7.png)

The objective of this assignment is to verify your skills in applying configuration management and Linux administration tools to install static web server on pre-deployed Linux based virtual machines.

In addition to verifying your skills of configuration management with Ansible, the assignment verifies your understanding of the modularized approach in configuration management with Ansible, ability to create code that will run on Debian and RPM based Linux distributions, and use of dynamic inventory in AWS to address the ephemeral nature of cloud environments.

As a result of this activity, you will create an Ansible playbook that installs a static website on the 2 Ubuntu and 2 Amazon Linux EC2 instances deployed in public subnets in multiple availability zones as outlined in the Section 2, Architecture diagram below. The Ansible playbook should rely on dynamic inventory and should not change following the re-creation of EC2 instances.

Cloud9 host acts as an Ansible control node and is used by admins to work with the dynamic inventory of EC2 instances.
