# 🚀 Node.js Click Counter App Deployed on AWS EC2

This is a simple click counter app I created and deployed on an AWS EC2 instance. This project shows my hands-on skills in cloud deployment using Ubuntu, Node.js, and AWS.

---

## 🛠️ What I Did

### ✅ Built a Node.js Web App

- Made a basic Node.js server with Express.
- Served frontend files with `express.static()`.
- Used `.env` to manage environment variables.

### ✅ Tested the App Locally

```bash
git clone https://github.com/af1nzr/clickounter-aws-ec2.git
cd clickounter-aws-ec2
npm install
npm run start

☁️ Deployed to AWS EC2 (What I Did)
🔐 Created an IAM User
Created an IAM user in AWS Console.

Assigned AdministratorAccess permission.

Enabled Programmatic Access for CLI/SDK use.

🖥️ Launched EC2 Instance
Selected Ubuntu Server 22.04 LTS as OS image.

Chose t2.micro instance (Free Tier eligible).

Created and downloaded a .pem key pair for SSH login.

🔗 Connected to EC2 Using SSH
ssh -i af1n-key.pem ubuntu@<EC2_PUBLIC_IP>
Replace <EC2_PUBLIC_IP> with your actual EC2 instance public IP.

🔄 Configured the EC2 Server
sudo apt update && sudo apt upgrade -y
sudo apt install git nodejs npm -y

📂 Deployed the App on EC2
git clone https://github.com/af1nzr/clickounter-aws-ec2.git
cd clickounter-aws-ec2
npm install
nano .env  # added PORT, DOMAIN, and other environment variables
npm run start

🌐 Accessing the App
Visited the app in browser using:
http://<EC2_PUBLIC_IP>:3000

You can also map it with a domain name using Route53 or any DNS provider.

✅ Skills Demonstrated
EC2 provisioning and Linux server management

SSH key handling and secure access

Node.js app setup in cloud

GitHub repo cloning and environment configuration

CLI usage, server startup, and firewall handling


