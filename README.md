## STIG & NIST 800-53 Compliance Playbook for Ubuntu Server

This Ansible playbook implements security controls based on STIGs, Security Requirements Guides, and NIST 800-53 for an Ubuntu server.

**Prerequisites:**

- Ansible installed and configured on your control machine.
- SSH access to the Ubuntu server.
- An inventory file listing the target server.

**Dependencies:**

- `apt` module
- `ufw` module
- `lineinfile` module
- `file` module
- `service` module
- `sysctl` module
- `copy` module

**Usage:**

1. Update the inventory file (`inventory/hosts`) with the target server's IP address or hostname.
2. Run the playbook: `ansible-playbook playbook.yml`

**Validation:**

The playbook includes tasks to check the compliance status after deployment. Review the output of the `debug` tasks for confirmation.

**Customization:**

- Modify the `vars/vars.yml` file to adjust security parameters as required.
- Add or remove roles based on your specific security requirements.
- Update the `auditd.rules` file with your custom audit rules.

**Disclaimer:**

This playbook is provided as a starting point for security hardening and compliance. It may require adjustments based on your specific environment and security policies.


**Testing:**

- Deploy this playbook on a test Ubuntu server.
- Verify the changes made by each role and task.
- Ensure all compliance checks pass successfully.

**Note:** This playbook is an example and should be tailored to **your** specific needs and environment. You will need to adjust the roles, tasks, and parameters based on **your** unique security requirements. 

You will need to modify the IP addresses, usernames, private key paths, and other parameters according to your environment, thought you likely shouldn't be using this. 

