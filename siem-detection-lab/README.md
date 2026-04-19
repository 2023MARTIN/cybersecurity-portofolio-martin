### 🛡️ SIEM Detection Lab

A blue-team focused project designed to simulate real-world security monitoring and detection using log analysis and alerting techniques in a cloud-based environment.

#### Key Activities
- Centralized log collection and analysis (Linux auth logs)
- Detection of brute-force attacks and unauthorized access attempts
- Creation of log-based detection rules (metric filters)
- Real-time alerting and notification setup
- Correlation of events with threat intelligence (GuardDuty)

#### Tools & Technologies
- AWS CloudWatch (Logs, Metrics, Alarms)
- Amazon GuardDuty (Threat Detection)
- Amazon SNS (Alerting)
- Linux (Ubuntu)
- SSH / Auth logs

#### Detection Scenarios
- SSH brute-force attempts (multiple failed logins)
- Suspicious authentication patterns
- Anomalous activity detected via GuardDuty findings

#### Outcomes
- Implemented real-time detection and alerting pipeline
- Reduced mean time to detection (MTTD)
- Improved visibility into system-level security events
- Strengthened incident response readiness

#### Security Improvements
- Hardened SSH configuration (key-based authentication)
- Restricted access via Security Groups
- Implemented automated alerting for rapid response

#### Disclaimer
This project was conducted in a controlled lab environment using authorized AWS resources only.
