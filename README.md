# AWS Security Monitoring & Threat Detection Lab

## 📌 Overview

This project demonstrates a cloud-based security monitoring system using AWS services to detect and respond to suspicious activity.

---

## 🛠️ Technologies Used

- **AWS CloudTrail** – API activity logging
- **Amazon CloudWatch** – Log monitoring and alerting
- **Amazon SNS** – Notification system
- **Amazon GuardDuty** – Threat detection
- **AWS CLI** – Attack simulation

---

## 🔐 Key Features

- Enabled multi-region logging of API activity using CloudTrail
- Implemented CloudWatch metric filters to detect:
  - Failed login attempts
  - Root account usage
- Configured automated alerts via SNS email notifications
- Enabled GuardDuty for intelligent threat detection
- Simulated attack scenarios to validate detection pipeline

---

## 🧪 Attack Simulations

- Repeated failed login attempts (brute-force simulation)
- AWS CLI reconnaissance activity (`describe-instances`, `list-users`)
- Observed logs in CloudTrail and triggered alerts in CloudWatch

---

## 📊 Results

- Successfully detected suspicious API activity
- Generated real-time alerts via SNS
- Verified monitoring pipeline end-to-end

---

## 💡 What I Learned

- How to monitor AWS environments in real time
- How attackers interact with cloud systems
- How to build detection and alerting pipelines