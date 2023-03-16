## Setup the ACS workshop environment

This directory contains Ansible playbooks to deploy and configure the ACS workshop environment.

### Prereqs
1. Request the "LPE Advanced Cluster Security" environment (demo.redhat.com)
2. Log in to your OpenShift cluster (as an admin user) with `oc login`
3. Install Ansible collections
   ```
   ansible-galaxy install -r requirements.yml
   ```

### Deploy
1. Execute `ansible-playbook site.yml`
2. Playbook will output required information
