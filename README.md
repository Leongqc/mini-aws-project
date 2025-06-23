# mini-aws-project
AWS Mini Cloud App – Audit Web Server (Free Tier Project)


A hands-on cloud project simulating a real-world internal audit web app using AWS core services — deployable fully within the AWS Free Tier.

---

## Architecture Overview

- EC2: Hosts Apache web server with custom message
- S3: Stores audit logs (uploaded every 30 mins)
- IAM: Role-based access for secure interaction
- CloudWatch: Monitors CPU and triggers alarms

---

## Features

- Auto-deploy EC2 web server via User Data
- Logs stored in `/var/log/app-access.log` and uploaded to S3 via cron
- IAM role with scoped permission to S3
- Custom CloudWatch alarm for high CPU usage

---

## Services Used

- Amazon EC2 (Amazon Linux)
- Amazon S3 (Private Bucket)
- AWS IAM (Roles & Policies)
- Amazon CloudWatch (Monitoring & Alarms)
- Bash / Cron / AWS CLI

---

## Learning Outcome

Demonstrated understanding of:
- Infrastructure-as-Code principles (User Data)
- IAM security best practices (roles vs access keys)
- Cloud-native monitoring and alerting
- Secure, low-cost AWS deployment patterns

---

## Demo Screenshot
![image](https://github.com/user-attachments/assets/cfb1e851-8ac5-4d27-bd9c-ed1bd9cf96d4)

(accessing my website)

![image](https://github.com/user-attachments/assets/6a8fc7e4-3234-4c94-9f65-225aeaa2ce0b)

(My log is transferred to S3)


