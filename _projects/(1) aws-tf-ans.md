---
name: Infrastructure Deployment on AWS
tools: [Terraform, Ansible, AWS, Django, PostgreSQL]
image: https://portfolio.fedunets.uk/assets/infra.png
description: This project demonstrates the use of Terraform and Ansible to automate the deployment of infrastructure on AWS.
---
## Project description
As the DevOps engineer for this project, my primary task was to deploy and configure servers for a new application utilizing the DigitalOcean team's Django sample app. The project involves employing Terraform to set up the infrastructure, which includes creating a VPC with both public and private networks. Three EC2 instances were to be deployed—two for the application in the public network and one for the database in the private network. SSM agent was configured and installed on instances using Terraform. Additionally, a Load Balancer was set up to distribute traffic among the application instances. An output file in inventory format for Ansible with Terraform is required
For Ansible, three roles were to be created. The first role is for infrastructure setup, responsible for installing Postgres on an instance and creating a user and database. The second role is for application instances, tasked with installing necessary software for the application and Nginx to proxy requests from port 80 to the Django application. The third role is for deployment, involving updating code from GitHub, updating the configuration with the current DB credentials, and executing DB migrations. 
This comprehensive approach ensures a streamlined deployment process, combining Terraform for infrastructure setup and Ansible for efficient configuration and deployment management.
## Project highlights
**Idempotency** - The playbook does not have any task using shell or command modules. This ensures the playbook is 100% idempotent.
**Transfering variables across plays and roles.** In the playbook I have two plays working with different inventory groups. One play works with DB server and another with application servers. There was a problem how to pass the DB connection string generated on the database host to the application hosts. I used a "dummy host" as a variable storage accessable in all roles.

<p class="text-center">
{% include elements/button.html link="https://github.com/dmytro108/itsynd/tree/master/week4-Ansible/task1" text="Learn More" %}
</p>