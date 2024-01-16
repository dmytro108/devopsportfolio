---
name: Peering a bunch of AWS VPCs
tools: [Terraform, AWS]
image: https://portfolio.fedunets.uk/assets/vpc-peer.png
description: 
---
## Project description
The project demonstrates how to create multiple VPCs and establish peering connections between them using Terraform. This is achieved by using Terraform's `for_each` loop and `count` feature. The peering connections are also created using the `for_each` loop, allowing for dynamic creation of peering connections between all VPCs.

This is a common scenario when you have multiple VPCs in different regions and you need to connect them together to allow communication between resources in different VPCs.

## Project highlights
This solution creates specified number of VPCs with specified number of public and private subnets dynamically generating all necessary CDRs. As well it dynamically creates peering connections between all of these **VPC**s in a each-to-each manner. 
![VPC peering](https://portfolio.fedunets.uk/assets/vpc-peer.png)

<p class="text-center">
{% include elements/button.html link="https://github.com/dmytro108/itsynd/tree/master/week1-VPC-peering/task3" text="Learn More" %}
</p>