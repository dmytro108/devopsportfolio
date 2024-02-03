---
name: Terraform-Driven Automation of Google Workspace with AI Assistance
tools: [Terraform, SOPS, Google Workspace, ChatGPT, Github Copilot]
image: https://portfolio.fedunets.uk/assets/googlews.png
description: Utilizing various AI tools for implementing a Terraform configuration the project showcases an approach to automating Google Workspace setups.
---
## Project description
This project combines Infrastructure as Code (IaC) and AI suggestions to improve how we set up Google Workspace, making the process smarter and more secure.

Setting up Google Workspace can be a time-consuming task. It requires a lot of manual work, which can be prone to human error. This is why I have decided to use Terraform to automate the process. However, I also want to make sure that the process is secure, and we are not exposing any sensitive information.

To address this issue, I have used SOPS to encrypt sensitive information such as passwords and API keys. SOPS is an open-source tool that makes it easy to manage secrets in your Git repository. It encrypts the files in your repository using PGP, and only authorized users can decrypt them. This way, we can safely store our secrets in our repository without worrying about exposing them.

I have also used ChatGPT and Github Copilot to assist us in writing our Terraform configuration. This AI-powered tools can suggest code snippets and complete your code as you type. This way, we can write our Terraform configuration faster and with fewer errors.  

## Project highlights
- Leveraged ChatGPT and Github Copilot to assist in writing Terraform configuration
- Utilized Terraform to automate the setup of Google Workspace
- Used SOPS to encrypt sensitive information in the Git repository

<p class="text-center">
{% include elements/button.html link="https://github.com/dmytro108/itsynd/tree/master/GoogleWS-admin" text="Learn More" %}
</p>