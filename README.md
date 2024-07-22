# setupDockerwithAnsible

This project provides an Ansible setup to install Docker and deploy an Nginx container. It is structured into two main roles:

## Roles

1. **Docker Installation**:
   - Installs Docker on the target system.
   
2. **Nginx Deployment**:
   - Pulls the Nginx Docker image.
   - Starts an Nginx container, mapping port 3000 on the host to port 80 in the container.

## Usage

To execute the playbook and run the roles, use the following command:

```bash
ansible-playbook main.yaml
