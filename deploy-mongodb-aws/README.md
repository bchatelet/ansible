# Deploy EC2 Instance (Ubuntu) with MongoDb with Ansible

This repository contains un Ansible playbooks for deploying an AWS EC2 instance, which contains a mongodb server.

## Prerequisites

- Ansible installed on your local machine.
- An AWS account with necessary permissions to create EC2 instance.
- SSH key pair (`ubuntu-aws-test1.pem`) for accessing the EC2 instance.

## Tasks

### Provision EC2 Instance

This playbook provisions a new EC2 instance in AWS, including the creation of 2 security groups.

- **Playbook:** `main.yml`

- **Usage:**
  
  ```bash
  ansible-playbook main.yml  
  ```
