# vmware_guest – Manages virtual machines in vCenter
For more details on vmware_guest, please visit:
https://docs.ansible.com/ansible/latest/modules/vmware_guest_module.html

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

vmdeploytemplate.yml
====================
Note:
* Does not include all configurations Ansible offers. Create template with desired configurations and modify needed changes in .yml