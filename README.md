# Ansible-Docker-Container
## Overview
This repository provides an Ansible playbook (`docker_deploy.yml`) crafted to automate the deployment of an Apache Docker container and configure its networking. The playbook is designed to simplify the deployment process, ensuring efficiency and consistency across various environments.

## Key Features
- **Automated Deployment:** Effortlessly deploy Apache Docker containers using Ansible.
- **Network Configuration:** Seamlessly configure networking for Docker containers to ensure uninterrupted connectivity.
- **Infrastructure as Code:** Define infrastructure configurations in code, facilitating version control and reproducibility.

## Requirements
To utilize this playbook effectively, ensure the following prerequisites are met:
- Ansible installed on the control machine.
- Docker installed on target hosts.

## Usage
Follow these steps to deploy the Apache Docker container using this playbook:
1. Clone this repository to your local machine:
git clone https://github.com/talhakhubaib/Ansible-Docker-Container.git

2. Navigate to the cloned repository directory:
cd ansible-docker-deployment

3. Execute the Ansible playbook:
ansible-playbook docker_deploy.yml


## Author
This playbook is maintained by Talha Khubaib.



