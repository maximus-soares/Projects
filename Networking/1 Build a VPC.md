<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a Virtual Private Cloud

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-networks-vpc)

**Author:** Maximus Soares  
**Email:** maximus@nextwork.org

---

## Build a Virtual Private Cloud (VPC)

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-vpc_2facf927)

---

## Introducing Today's Project!

### What is Amazon VPC?

Amazon VPC is a useful tool to help create virtual private clouds to help organise subnets and security rules of different but similar resources. 

### How I used Amazon VPC in this project

We used Amazon VPC today by setting up a VPC, then a subnet and finally an Internet Gateway, 

### One thing I didn't expect in this project was...

I didn't expect to already have exisiting VPC's and subnets included in my gallery. 

### This project took me...

This project took me 1 hour. 

---

## Virtual Private Clouds (VPCs)

VPC's are a Virtual Private Clouds'. They essentially act as our own private city within a cloud network. You are then able to control the security measures, traffic rules, and control the subnets within. Nice!

There is a default VPC in our AWS account as services like EC2 require a VPC in order to run so that our resources do not become publicly available when we didn't want them to be. AWS includes the default VPC so users can deploy services quickly. 

To set up my VPC, I had to define an IPv4 CIDR, which is equivalent to a IP Address. A CIDR, is a way to assign a whole block of IP addresses.

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-vpc_2facf927)

---

## Subnets

Subnets are like the different neighbourhoods with the city (VPC). They allow the grouping of similar resources with similar security settings and controls. Some may be Private and some may be public. 

There are already subnets existing in my account, one for every 3 Availability Zones within a region. 

I named my subnet Public 1, but that doesn’t automatically make my subnet a public subnet. For a subnet to be considered public, it has to go through an internet gateway.

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-vpc_157c4219)

---

## Internet gateways

Internet gateways are a method to connect VPC's to the internet

Attaching an internet gateway to a VPC means that now the VPC can access internet and the EC2s can also become accessible through the internet. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-vpc_4ae90410)

---

## Using the AWS CLI

---

---
