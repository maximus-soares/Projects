<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Set Up a Web App in the Cloud

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-devops-vscode)

**Author:** Maximus Soares  
**Email:** maximus@nextwork.org

---

## Set Up a Web App Using AWS and VS Code

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-devops-vscode_7a1de541)

---

## Introducing Today's Project!

Today I will be setting up a basic web app + using VS Code. Which will help lay the foundations for my DevOps CI/CD pipeline. 


### Key tools and concepts

 absolutely free to install and use, so we'd recommend keeping it in your local computer. It's a great tool for future projects and you'll need it again for the rest of this DevOps series.

### Project reflection

his DevOps series.

de is absolutely free to install and use, so we'd recommend keeping it in your local computer. It's a great tool for future projects and you'll need it again for the rest of this DevOps series.

out VSCode?
VSCode is absolutely free to install and use, so we'd recommend keeping it in your local computer. It's a great tool 

---

## Launching an EC2 instance

I started this project by launching an EC2 instance because I needed a virtual machine to be able to run our web app entirely on the cloud.

### I also enabled SSH

SSH is a way to connect to a remote server in a secure manner. I enabled SSH so that I could only get access to my EC2 instance, as I was the only one with the private key. It also means that all the data that I transfer is encrypted. 

### Key pairs

A key pair is key to our virtual machine, consisting of a public half and a private key. 

Once I set up my key pair, AWS automatically downloaded my private key in a .pem file.

---

## Set up VS Code

VSCode is an IDE


I installed VSCode to communicate with my EC2 instance.

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-devops-vscode_53d05e68)

---

## My first terminal commands

A terminal is... The first command I ran for this project is

I also updated my private key's permissions by

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-devops-vscode_9328ada1)

---

## SSH connection to EC2 instance

To connect to my EC2 instance, I ran the command

### This command required an IPv4 address

A server's IPV4 DNS is

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-devops-vscode_e3069dca)

---

## Maven & Java

💡 What is Apache Maven?
Apache Maven is a tool that helps developers build and organize Java software projects. It's also a package manager, which means it automatically download any external pieces of code your project depends on to work.

Maven is required in this project because

Java is

Start your response with 'Java is required in this project because'...



---

## Create the Application

I generated a Java web app using the command

✍️ Why did you install Remote - SSH?
Start your answer with 'I installed Remote - SSH, which is... I installed it to'...



✍️ What was in the configuration file?
Start your answer with 'Configuration details required to set up a remote connection include'...



![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-devops-vscode_2939cf01)

---

## Create the Application

tart your answer with 'Using VSCode's file explorer, I could see'...

✍️ What are the src and webapp folders?
Start your answer with 'Two of the project folders created by Maven are src and webapp, which'...



![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-devops-vscode_45f91fd7)

---

## Using Remote - SSH

Start your answer with 'index.jsp is'...

✍️ How did you edit index.jsp?
Start your answer with 'I edited index.jsp by'...

![Image](http://learn.nextwork.org/happy_maroon_jolly_red_currant/uploads/aws-devops-vscode_7a1de541)

---

## Using nano

---

---
