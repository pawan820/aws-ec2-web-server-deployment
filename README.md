AWS EC2 Web Server Deployment

Project Overview

This project demonstrates how to deploy a simple static website on an Amazon EC2 instance using the Apache HTTP Server.

Technologies Used

- Amazon Web Services (AWS)
- Amazon EC2
- Linux
- Apache HTTP Server
- HTML
- CSS
- SSH

Project Features

- Launch an EC2 virtual machine.
- Configure security groups.
- Connect to the instance using SSH.
- Install and configure Apache.
- Deploy a custom HTML website.
- Access the website using the EC2 public IP address.

Project Structure

aws-ec2-web-server-deployment/
├── index.html
└── README.md

Deployment Steps

1. Launch an Amazon EC2 instance.
2. Configure inbound rules for SSH (port 22) and HTTP (port 80).
3. Connect to the instance using SSH.
4. Install Apache HTTP Server.
5. Start and enable the Apache service.
6. Upload "index.html" to the Apache web root directory.
7. Open the EC2 public IPv4 address in a browser.

Website Location

Apache default document root:

/var/www/html/

Test

Open the following address in a browser after deployment:

http://YOUR-EC2-PUBLIC-IP

Security Notes

- Never upload private SSH keys to GitHub.
- Allow SSH access only from trusted IP addresses.
- Do not expose unnecessary ports.
- Protect AWS account credentials.

Author

Pawan Anil Mohite

GitHub: https://github.com/pawan820
