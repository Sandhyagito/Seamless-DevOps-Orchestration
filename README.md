# Seamless-DevOps-Orchestration
Highlights the end-to-end setup from infrastructure from Terraform Automation to Kubernetes Deployment

# Project Title: Seamless-DevOps-Orchestration: Terraform, Ansible, Docker & Kubernetes
# Description:

Established a seamless deployment pipeline on AWS, integrating Terraform, Ansible, and Docker for efficient infrastructure provisioning and application deployment.

# Terraform & AWS Setup:
•	Configured Terraform workstation on AWS for infrastructure as code management.
•	Enabled secure SSH access via Instance Connect.
•	Installed Terraform and AWS CLI, configuring credentials for AWS service interaction.
•	Created Terraform configuration (.tf) files for EC2 instances and SSH keys, generating a secure SSH key pair.
# Ansible Deployment:
•	Established SSH connectivity between Terraform and Ansible workstations.
•	Installed Ansible, managing host configurations via inventory files.
•	Deployed a custom HTTPd web server using Ansible YAML configuration.
•	Verified deployment success, ensuring consistent server setup.
# Dockerized Application Deployment:
•	Built and pushed a custom Docker image to DockerHub.
•	Created a Kubernetes pod using custom Docker image YAML configuration.
•	Exposed the pod for external access, facilitating seamless deployment and scalability.

# Challenges:
- Resolved Terraform key pair attachment issue by creating a dedicated AWS key pair resource file, enabling secure SSH access to Ansible-managed instances.
- Troubleshot and fixed Apache HTTP Server configuration using Ansible, ensuring the custom 'index.html' page was correctly served, resulting in improved web service delivery.

