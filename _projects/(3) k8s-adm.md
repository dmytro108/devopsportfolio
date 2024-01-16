---
name: Django on Kubernetes with Helm and TLS Security
tools: [Kubernetes, Helm, Helmfile, SOPS, Let'sencrypt, DigitalOcean]
image: https://portfolio.fedunets.uk/assets/cluster.png
description: As part of technological evolution of my skills, I embarked on a project to leverage Kubernetes for container orchestration, ensuring scalability and robust management of a new web application in the cloud.
---
## Project description
The goal was to launch a new web application in the cloud, making it both secure and scalable. I aimed to showcase our ability to efficiently manage containerized applications using Kubernetes while ensuring the application stays available, even during high user demand.

This project highlights my expertise in deploying and managing cloud-based applications, emphasizing security, scalability, and reliable access. It demonstrates my proficiency in orchestrating containers using Kubernetes and Helm.

The project uses DigitalOcean's managed Kubernetes service, Helm for package management, and Let's Encrypt for TLS certificates. To ensure secure storage of sensitive data, I used SOPS to encrypt and decrypt secrets.

The project also includes a Helmfile, which allows for easy deployment and management of the application, including the ability to update the application with zero downtime.

![K8s infrastructure](https://portfolio.fedunets.uk/assets/infra.png)

## Project highlights
1. Using Helmfile hooks
1. Automaticaly generating and managing TLS certificates with Let's Encrypt
1. Secure storage of sensitive data with SOPS
1. Updating dynamic DNS records with Namecheap API
1. Utilizing Configmaps, Secrets, Persistance storage, and Ingress resources in Kubernetes
1. Utilizing liveness and readiness probes to ensure application availability
1. Configuring Horizontal Pod Autoscaling (HPA) to handle high user demand

<p class="text-center">
{% include elements/button.html link="https://github.com/dmytro108/itsynd/tree/master/week7-Kubernetes/task1" text="Learn More" %}
</p>