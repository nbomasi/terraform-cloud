# AUTOMATE INFRASTRUCTURE WITH IAC USING TERRAFORM – TERRAFORM CLOUD

This project introduces us to the concept of terraform cloud which is explained below:

**Terraform Cloud** is a managed service that provides you with Terraform CLI to provision infrastructure, either on demand or in response to various events.

By default, Terraform CLI performs operation on the server whenever it is invoked, it is perfectly fine if you have a dedicated role who can launch it, but if you have a team who works with Terraform – you need a consistent remote environment with remote workflow and shared state to run Terraform commands.

This Project is a continuation of project 18, however, the following will be added:

The files that would be Addedd is;

**PACKER:** for building AMI images

Packer is an open source tool for creating identical machine images for multiple platforms from a single source configuration. Packer is lightweight, runs on every major operating system, and is highly performant, creating machine images for multiple platforms in parallel.

**ANSILE:** for Ansible scripts to configure the infrastucture

**Installing Packer:** 

Packer was installed with chocolatey pcakage manager with the following command: ```markdown
choco install packer
```

## BOTO

Boto is a software development kit (SDK) designed to improve the use of the Python programming language in Amazon Web Services. The Boto project started as a customer-contributed library to help developers build Python-based applications in the cloud, converting application programming interface (API) responses from AWS into Python classes.

Boto has become the official AWS SDK for Python. Boto versions include Boto, Boto3 and Botocore. Boto3 is the latest version of the SDK, providing support for Python versions 2.6.5, 2.7 and 3.3. Boto3 includes several service-specific features to ease development. Boto supports all current AWS cloud services, including Elastic Compute Cloud, DynamoDB, AWS Config, CloudWatch and Simple Storage Service.

Boto3 replaced Boto version 2, which lacks compatibility with the latest versions of Python, but still appeals to software developers using older versions of the programming language. Botocore provides more rudimentary access to AWS tools, simply making low-level client requests and getting results from APIs.

Boto derives its name from the Portuguese name given to types of dolphins native to the Amazon River.