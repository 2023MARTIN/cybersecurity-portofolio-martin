# AWS Pentest & Threat Detection Lab

##  Overview
This project demonstrates how to simulate controlled security events on an AWS EC2 instance and analyze detection mechanisms using **Amazon GuardDuty** and **Amazon CloudWatch**.

The goal is to showcase real-world cloud security skills including:
- Threat detection
- Log analysis
- Incident response
- Security hardening

---

##  Architecture

- AWS EC2 (Ubuntu Server)
- Amazon GuardDuty (Threat Detection)
- Amazon CloudWatch (Monitoring & Alerts)
- SNS (Email Notifications)

---

##  Technologies Used

- AWS EC2
- Amazon GuardDuty
- Amazon CloudWatch
- Amazon SNS
- Linux (Ubuntu)
- SSH

---

## Lab Scenarios

### 1. SSH Brute Force Simulation
Multiple failed SSH login attempts were generated to simulate unauthorized access.

```bash
ssh fakeuser@<EC2-PUBLIC-IP>
