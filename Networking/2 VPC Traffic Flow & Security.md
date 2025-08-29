<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# VPC Traffic Flow and Security

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-networks-security)

**Author:** Maximus Soares  
**Email:** maximus@nextwork.org

---

## VPC Traffic Flow and Security

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-security_92b0b0b4)

---

## Introducing Today's Project!

### What is Amazon VPC?

Amazon VPC is a virtual private cloud. You can think of it as creating a City within a country where you can control the rules and who goes in and out of the city. 

### How I used Amazon VPC in this project

We used Amazon VPC in today's project by setting up our own VPC, which we then created subnets in, attached a internet gateway to out VPC. 

### One thing I didn't expect in this project was...

I didn't expect that the public subnet would route traffic to the internet gateway. 

### This project took me...

This project took 30 minutes

---

## Route tables

Route tables essentially direct the traffic within the subnet to their respective destinations. 

Routes tables are needed to make a subnet public because as the subnet needs a way to the internet 
gateway to make resources public. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-security_0a07b191)

---

## Route destination and target

Routes are defined by their destination and target, which mean The IP address range that traffic wants to reach, and the road or path that the traffic will have to take to get to its destination.

The route in my route table that directed internet-bound traffic to my internet gateway had a destination of 0.0.0.0/0 and a target of igw-01a83bd1bdae78b7d

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-security_0a07b191)

---

## Security groups

Security groups are the guard at the entrance for resource in a subnet. 


### Inbound vs Outbound rules

Inbound rules are visitors to your sight that your website recieves from submissions for. I configured an inbound rule to allow HTTP traffic from "0.0.0.0/0" (meaning any IP address) is typical and necessary for public subnets

Outbound rules are already enabled. By default, my security group's outbound rule is that all traffic is allowed. 

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-security_92b0b0b4)

---

## Network ACLs

Network ACLs check each data packet against a table of ACL rules before allowing them through.


### Security groups vs. network ACLs

The difference between a security group and a network ACL is that Network ACLs apply to the subnet and security groups apply to the resources. 

---

## Default vs Custom Network ACLs

### Similar to security groups, network ACLs use inbound and outbound rules

By default, a network ACL's inbound and outbound rules will allow all traffic. 

In contrast, a custom ACL’s inbound and outbound rules are automatically set to denying traffic.

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-networks-security_4faeb056)

---

## Tracking VPC Resources

---

---
