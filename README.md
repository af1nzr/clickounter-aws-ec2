# Node.js Click Counter App Deployed on AWS EC2

This is a simple click counter app I created and deployed on an AWS EC2 instance. This project demonstrates my skills in cloud deployment, Linux server setup, and Node.js development.

---

##  What I Did

### Created an IAM User
- Created an IAM user in the AWS Console.
- Assigned AdministratorAccess permission.
- Enabled Programmatic Access for CLI and SDK use.

### Launched EC2 Instance
- Operating System: Ubuntu Server 22.04 LTS
- Instance type: t2.micro (Free Tier eligible)
- Created and downloaded a new `.pem` key pair for SSH login.

### Connected to EC2 Using SSH
- Used SSH with the downloaded `.pem` file to connect to the EC2 instance.
- Replaced the placeholder with the actual EC2 public IP address.

### Configured the EC2 Server
- Updated and upgraded all packages on the server.
- Installed Git, Node.js, and npm.

### Deployed the App on EC2
- Cloned the project repository to the EC2 instance.
- Installed the required Node.js dependencies.
- Created and configured the `.env` file with environment variables such as PORT and DOMAIN.
- Started the Node.js application.

### Exposed the App to the Internet
- Edited the inbound rules in the EC2 security group.
- Allowed incoming traffic on the app’s port (for example, port 3000).

---

## Summary

I successfully built and deployed a Node.js click counter app on AWS EC2. This involved setting up IAM users, launching and configuring an EC2 instance, and deploying the app using Git and Node.js. I also ensured proper network security by configuring security group rules.
