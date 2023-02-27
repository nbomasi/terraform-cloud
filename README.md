# AUTOMATE INFRASTRUCTURE WITH IAC USING TERRAFORM – TERRAFORM CLOUD

This project introduces us to the concept of terraform cloud which is explained below:

**Terraform Cloud** is a managed service that provides you with Terraform CLI to provision infrastructure, either on demand or in response to various events.

By default, Terraform CLI performs operation on the server whenever it is invoked, it is perfectly fine if you have a dedicated role who can launch it, but if you have a team who works with Terraform – you need a consistent remote environment with remote workflow and shared state to run Terraform commands.

This Project is a continuation of project 18, however, the following will be added:

The files that would be Addedd is;

**AMI:** for building packer images
**Ansible:** for Ansible scripts to configure the infrastucture

**Installing Packer:** 

Packer was installed with chocolatey pcakage manager with the following command: ```markdown
choco install packer
```