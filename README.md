# AWS EC2 Apache Web Server Project

This repository contains the process and documentation for launching a basic web server on an Amazon EC2 instance.

## 🚀 Project Description

The goal of this project was to learn the fundamentals of cloud computing with AWS. This involved provisioning a virtual server (EC2), configuring its network and security settings, connecting to it via SSH, and installing and running an Apache web server to serve a simple HTML page.

## ✨ Key Features

-   **EC2 Instance:** Launched a `t2.micro` instance using the Amazon Linux 2 AMI.
-   **Security:** Configured a Security Group to allow inbound HTTP (port 80) and SSH (port 22) traffic.
-   **Web Server:** Installed and enabled Apache (`httpd`).
-   **Custom Page:** Served a custom `index.html` page.

## ⚙️ Technologies Used

-   Amazon Web Services (AWS)
    -   EC2 (Elastic Compute Cloud)
    -   VPC (Security Groups)
-   Linux (Amazon Linux 2)
-   Apache Web Server (`httpd`)
-   SSH
-   Bash/Shell Scripting

## 📋 Step-by-Step Process

The main steps taken to complete this project were:
1.  Created a key pair for secure SSH access.
     ![Secrete Access Key](https://github.com/Tooddlez/Creating-an-EC2-Instance-and-installing-an-Apache-web-server-on-it/blob/main/Secret%20Acess%20Key.PNG)
2.  Launched the EC2 instance, configuring the AMI, instance type, and security group.
3.  Connected to the instance using an SSH client.
    ![Inbound Rule](https://github.com/Tooddlez/Creating-an-EC2-Instance-and-installing-an-Apache-web-server-on-it/blob/main/Inbound%20Rule1.PNG)
4.  Updated the system packages using `sudo yum update -y`.
5.  Installed Apache with `sudo yum install httpd -y`.
    ![Secrete Access Key](https://github.com/Tooddlez/Creating-an-EC2-Instance-and-installing-an-Apache-web-server-on-it/blob/main/Installed%20an%20Apache%20server%20on%20a%20Linux%20EC2%20Istance.PNG)
6.  Started and enabled the Apache service.

## 📸 Final Result

Here is a screenshot of the final web page being served by the EC2 instance:

![Apache Web Server running on EC2](https://github.com/Tooddlez/Creating-an-EC2-Instance-and-installing-an-Apache-web-server-on-it/blob/main/The%20Apache%20Web%20Server%20is%20running.PNG)
