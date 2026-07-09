# AWS DevOps Intern Assignment

## EC2 Setup
- Launched Ubuntu 26.04 LTS t2.micro instance (free tier)
- Security Group: SSH (22) restricted to my IP, HTTP (80) open to all
- Connected via SSH using key pair (assignment.pem)
- Public IP: 98.84.132.140

## Nginx Installation
sudo apt update && sudo apt upgrade -y
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx

## Website Deployment
- Replaced /var/www/html/index.html with custom page containing name, college, branch, email, date
- Verified access via public IP: http://98.84.132.140

## Commands Used
df -h       # disk usage
free -h     # memory usage
top         # running processes

