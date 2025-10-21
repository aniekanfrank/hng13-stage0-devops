# 🧠 HNG Internship - DevOps Stage 0: Web Server Deployment

## 📋 Project Overview
This project was part of the HNG Internship (Stage 0 – DevOps Track).  
The task was to deploy a custom NGINX web server on a cloud-hosted VPS (AWS EC2), serving a personalized HTML page accessible to the public internet.  
It demonstrates my understanding of fundamental DevOps and Cloud Engineering concepts — from cloud provisioning to web server configuration and network security.

---

## 🚀 Key Achievements
- Launched and configured an **AWS EC2 instance**.
- Installed and set up **NGINX** on Port 80.
- Created a **custom index.html** page with my HNG details.
- Configured **AWS Security Groups** to allow external HTTP access.
- Managed version control and documentation via **Git and GitHub**.

---

## 🧰 Tech Stack
- **AWS EC2**
- **NGINX**
- **Amazon Linux 2**
- **Git / GitHub**
- **Security Groups**

---

## 🖥️ Live Demo
🌐 [http://3.87.77.9](http://3.87.77.9)

---

## ⚙️ Deployment Steps (Summary)
1. **Launched** an EC2 instance on AWS (Amazon Linux 2).  
2. **Connected** via SSH using the key pair.  
3. **Installed NGINX** using the command:  
   ```bash
   sudo yum install nginx -y

 Install and Configure NGINX
sudo dnf install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx

sudo cp index.html /usr/share/nginx/html/index.html
