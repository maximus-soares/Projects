<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Creating a Private Subnet

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-networks-private)

**Author:** Maximus Soares  
**Email:** maximus@nextwork.org

---

## Creating a Private Subnet

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-private_afe1fdbd)

---

## Introducing Today's Project!

### What is Amazon VPC?

Amazon VPC lets you carve out your own private section of the AWS cloud, so you can control traffic, secure your resources, and build cloud apps safely.

### How I used Amazon VPC in this project

We used Amazon VPC today by creating our own private subnet with a unique CIDR block, setting up a dedicated route table without internet access, and configuring a custom network ACL that denies all inbound and outbound traffic by default - giving me full control over what’s allowed in or out.

### One thing I didn't expect in this project was...

I didn’t expect that we wouldn’t touch the security groups for our private subnet in this project -  but it makes sense now, since security groups are applied to individual resources, and we haven’t launched anything inside that subnet yet.

### This project took me...

40mins

---

## Private vs Public Subnets

The difference between public and private subnets is that 
Public = IGW route + Public IP
Private = No IGW route

Having private subnets are useful because private subnets reduce risk, improve security, and enforce control over what talks to the outside world - critical for real-world production architecture.

My private and public subnets cannot have the same CIDR block. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-private_afe1fdbd)

---

## A dedicated route table

By default, my private subnet is associated with the VPC’s main route table, which includes a local route that enables communication between all resources inside the VPC.

I had to set up a new route table because the default (main) route table had a route to the internet gateway, which would have made your private subnet public if you reused it.

My private subnet's dedicated route table only has one inbound and one outbound rule that allows a local route that enables internal communication within the VPC.

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-private_b4b904b5)

---

## A new network ACL

By default, my private subnet is associated with a default network ACL and the main route table. 

I set up a dedicated network ACL for my private subnet because I don't want to allow all traffic.

My new network ACL has two simple rules - inbound and outbound will be denied. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-private_1ed2cb07)

---

---
