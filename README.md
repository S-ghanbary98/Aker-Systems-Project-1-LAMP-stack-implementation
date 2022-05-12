# Aker-Systems-Project-1-LAMP-stack-implementation

## Intro

In this project, I will employ a LAMP (Linux, Apache, MySQL, PHP) stack project in an amazon EC2 instance. Here are the steps I took to implement this.\


### Initial Amazon EC2 Spin-Up & Appache Installation.

- Firstly, I used my aws account free tier to spin up an ec2 with ubuntu 18:0 as the OS. Furthermore, I changed the inbound security group to allow http, to later see the output on the web.
- the following commmand was run `sudo apt update && sudo apt install apache2 && sudo systemctl status apache2` to update, install and check apache's status.

![alt text](images/firewall.png)

![alt text](images/Installation%20of%20Apache.png)

![alt text](images/apache%20status.png)


###

