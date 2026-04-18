# SIEM Detection Lab (AWS)

## Overview
This project demonstrates how to build a lightweight SIEM detection environment in AWS using **Amazon CloudWatch**, **Amazon GuardDuty**, and log-based alerting techniques.

The objective is to simulate security events, collect logs, detect suspicious behavior, and generate real-time alerts — similar to a real Security Operations Center (SOC).

---

##  Objectives

- Collect and analyze logs from an EC2 instance
- Detect suspicious activities (SSH brute force, failed logins)
- Generate alerts using CloudWatch
- Correlate findings with GuardDuty
- Implement basic incident response actions

---

##  Architecture

- EC2 (Ubuntu Linux)
- Amazon CloudWatch Logs
- Amazon CloudWatch Alarms
- Amazon GuardDuty
- Amazon SNS (Email Alerts)

---

##  Technologies Used

- AWS EC2
- Amazon CloudWatch
- Amazon GuardDuty
- Amazon SNS
- Linux (Ubuntu)
- SSH / Auth logs

---

##  Detection Scenarios

### 1. SSH Brute Force Detection

Simulated multiple failed login attempts:

```bash
ssh fakeuser@<EC2-PUBLIC-IP>
