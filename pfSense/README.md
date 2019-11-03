Verified for following:
=======================
* VMware vCenter Server Appliance:
  * Version: 6.7.0.40000
  * Build #: 14367737

Requirements for Ansible:
=========================
The below requirements are needed on the host that executes this module:
- python >= 2.6
- PyVmomi

Requirements for templates:
===========================
The below requirement are needed for Linux
- open-vm-tools package
- Perl package

The below requirement are needed for Windows
- VMware Tools

full_pfsense_deploy.yml
====================
Runs the two playbooks (deploy_pfsense.yml & conf_pfsense.yml).

deploy_pfsense.yml
====================
Creates pfSense from template and modifies distributed port groups.

conf_pfsense.yml
====================
Copys your pfSense config.xml to your remote router, clear config.cache, and reboot.