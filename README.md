Network Security Assessment & Secure Architecture Redesign
Tools: Nmap, Wireshark, draw.io, Microsoft PowerPoint
Type: Defensive Security | Network Architecture | Risk Assessment


Overview
Conducted a comprehensive cybersecurity assessment for a simulated mid-sized aerospace manufacturer preparing to meet government contract security requirements. Identified critical vulnerabilities across the organization's existing infrastructure and designed a full secure network architecture redesign.

This project was completed as part of the Cybersecurity Engineering program at Flatiron School.


Objectives
Assess the current security posture of the organization
Identify vulnerabilities and compliance gaps
Design a secure network architecture addressing all identified risks
Present findings and recommendations to simulated executive stakeholders


Key Vulnerabilities Identified
Default Credentials — Critical systems accessible with factory-set usernames and passwords
No Multi-Factor Authentication (MFA) — Single-factor authentication across all user accounts
Flat Network Architecture — No segmentation between departments or sensitive systems
Patch Management Gaps — Outdated software versions across multiple endpoints
Insecure File Transfer — Unencrypted FTP in use for sensitive data transfers


Secure Architecture Redesign
Designed a layered security architecture incorporating:
🔒 Network Segmentation
VLAN segmentation separating departments, servers, and guest networks
Limits lateral movement in the event of a breach
🛡️ DMZ Architecture
Isolated demilitarized zone for public-facing services
Prevents direct access to internal network from the internet
🚨 Intrusion Detection & Prevention
IDS/IPS deployment for real-time threat detection and automated blocking
Monitors for anomalous traffic patterns and known attack signatures
🔐 Secure File Transfer
SFTP enforcement replacing unencrypted FTP
Ensures all file transfers are encrypted in transit
👤 Identity & Access Management
MFA enforcement across all user accounts
Principle of least privilege applied to all roles


Deliverables
Security Assessment Report — Documented all vulnerabilities with severity ratings and business impact
Network Architecture Diagram — Visual redesign of the secure infrastructure
Stakeholder Presentation — Executive-facing slide deck with staged rollout timeline and cost-benefit analysis


Staged Rollout Timeline
Phase
Priority
Actions
Phase 1
Critical
Change default credentials, enforce MFA
Phase 2
High
Implement VLAN segmentation and DMZ
Phase 3
Medium
Deploy IDS/IPS, enforce SFTP
Phase 4
Ongoing
Patch management and security monitoring



Demo
📹 Watch the full project walkthrough
https://www.youtube.com/watch?v=tXKywFuxSFU

📊 [View project overview]
(https://www.linkedin.com/in/mac-coderre-562513214/overlay/Project/1619464519/treasury/?profileId=ACoAADYuZFoBLN7msBREN-rSLg4H7qEaxXCrXq0)

Skills Demonstrated
Network Security Network Architecture VLAN Design DMZ Architecture IDS/IPS Risk Assessment Vulnerability Assessment Security Reporting Stakeholder Communication SFTP
