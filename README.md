# Cybersecurity Home Projects Portfolio

Welcome to my Cybersecurity Home Projects portfolio! This repository showcases the various projects I’ve undertaken to hone my skills in threat detection, network security, and system hardening. These projects involve real-world tools, methodologies, and problem-solving approaches.

---

## Table of Contents
- [Overview](#overview)
- [Projects](#projects)
  - [1. Honeypot Deployment and Threat Intelligence](#1-honeypot-deployment-and-threat-intelligence)
  - [2. Nmap XMAS Scan Detection and Mitigation](#2-nmap-xmas-scan-detection-and-mitigation)
  - [3. SCADA System Security Design](#3-scada-system-security-design)
  - [4. SIEM Log Analysis and Threat Hunting](#4-siem-log-analysis-and-threat-hunting)
  - [5. Digital Forensics Android Biopsy]()
- [Tools and Technologies](#tools-and-technologies)
- [Future Goals](#future-goals)

---

## Overview

This portfolio reflects my passion for cybersecurity and my dedication to mastering the defensive side of the field. Through self-driven projects, I’ve gained hands-on experience with concepts like network monitoring, vulnerability assessment, and threat intelligence gathering. Each project is documented to showcase the steps, tools, and outcomes.

---

## Projects

### 1. Honeypot Deployment and Threat Intelligence

**Objective:** To gather threat intelligence by deploying a honeypot and monitoring attack patterns.  
**Steps Taken:**
- Configured a [honeypot tool] to simulate vulnerable services.
- Analyzed malicious traffic using Splunk and Wireshark.
- Logged attack patterns to identify common techniques used by attackers.
- Automated monitoring and alerting mechanisms.

**Outcome:** Collected valuable insights into real-world attack vectors, improving understanding of threat actor behavior.

**Link to Artifact:** [HoneyPot Development](https://github.com/VernonXTA/Simple-SSH-HoneyPot)

---

### 2. Nmap XMAS Scan Detection and Mitigation

**Objective:** To detect and block an Nmap XMAS scan targeting a web server.  
**Steps Taken:**
- Identified the XMAS scan targeting port 80 on an Apache2 web server.
- Configured `iptables` to dynamically block the attacker’s IP address.
- Hardened the server by dropping malformed and stealthy packets.
- Verified the mitigation using testing tools.

**Outcome:** Successfully mitigated the attack, ensuring server availability and security.

**Link to Artifact:** [IPS with Snort](https://github.com/VernonXTA/UbuntuIDS)

---

### 3. SCADA System Security Design

**Objective:** To design a secure architecture for SCADA systems in the water treatment industry.  
**Steps Taken:**
- Developed a Level 4 business-side SCADA design, integrating secure communication protocols.
- Incorporated CRM and data recovery solutions for business continuity.
- Analyzed potential vulnerabilities and proposed mitigation strategies.

**Outcome:** Created a robust design framework for securing industrial control systems.

**Link to Artifact:** [Scada Security Design](https://github.com/VernonXTA/SCADA-System-Security-Design)

---

### 4. SIEM Log Analysis and Threat Hunting

**Objective:** To analyze security logs and identify potential threats using a Security Information and Event Management (SIEM) system.  
**Steps Taken:**
- Collected and ingested security logs from multiple sources into a SIEM platform.
- Created detection rules and correlation alerts for suspicious activity.
- Investigated real-world attack scenarios such as brute-force attempts and unauthorized access.
- Generated reports and recommendations for incident response.

**Outcome:** Enhanced threat detection capabilities and improved response strategies through log analysis and pattern recognition.

**Link to Artifact:** [SiemLab](https://github.com/VernonXTA/SIEM-Lab)

---

### 5. Side Projects For Python

**Objective:** This one is more of a fun project side of mine, which incorporates my favorite hobby which is Cosmology and Astrophysics.
**No Steps Taken. Just For Fun.**
- Created a program that simulates the Milky Way Galaxy and uses Nasa's Galactic Coordination System for Encryption with high entropy.
- Created a program that uses the Penrose Process and compares it to Dyson Sphere calculations.

**Outcome:** Had a lot of fun doing all of these! They just pop in my head and write them out in code for fun!

**Link to Artifacts:** [Cosmology Projects](https://github.com/VernonXTA/Cosmic-Energy-Calculator)

## Tools and Technologies

Throughout these projects, I’ve worked with:
- **Security Tools:** Splunk, Wireshark, iptables, SIEM platforms
- **Networking Tools:** Cisco Packet Tracer
- **Programming Languages:** Python
- **Virtualization:** VMware
- **Operating Systems:** Linux (Ubuntu), Windows Server

---

## Future Goals

- Explore automated threat detection using machine learning.
- Develop custom scripts for vulnerability assessment.
- Gain hands-on experience with cloud security platforms.

---

## Contact

If you’re interested in my work or would like to collaborate, feel free to reach out via [dantehenningsen@gmail.com].

---
