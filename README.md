# HeatOrchestration

What is Heat?
Heat is the main project of the OpenStack orchestration program. It allows users to describe deployments of complex cloud applications in text files called templates. These templates are then parsed and executed by the Heat engine.

What is ansible?
Ansible is software that automates software provisioning, configuration management, and application deployment.

Prerequisites:
Openstack Installation done using DevStack or any other OpenStack distribution that includes Heat. 
Ansible should be installed.

Steps to execute:
1. Clone the repo.
2. Source adminrc_keystone file
3. Change directory to HeatOrchestration/ansible `cd HeatOrchestration/ansible`
4. To create demo environment using ansible playbook: `ansible-playbook demo.yml -c local -vv`
