# Damn Vulnerable Web Application (DVWA) Lab

This folder contains notes, configurations, and scripts related to my testing and learning with the **Damn Vulnerable Web Application (DVWA)**. DVWA is a deliberately vulnerable PHP/MySQL web app used to practice common web vulnerabilities and sharpen ethical hacking skills.

---

## 🧪 Lab Purpose

This lab is designed to simulate real-world web application vulnerabilities and apply hands-on practice with:

- OWASP Top 10 vulnerabilities  
- Web application penetration testing techniques  
- Manual and automated exploitation  
- Tools like Burp Suite, sqlmap, curl, and browser DevTools

---

## ⚙️ Setup Instructions

### Prerequisites:
- Docker & Docker Compose  
- Kali Linux or any pentesting distro  
- Git (optional)
 --- 
🛠️ Tools Used
- Burp Suite Community Edition – Intercepting and manipulating HTTP requests
- sqlmap – Automated SQL injection testing
- curl / wget – Command-line HTTP testing
- Kali Linux – Testing environment
- Browser DevTools – Inspect and modify web requests
---
🧠 Vulnerabilities Practiced
- SQL Injection (SQLi)
- Command Injection
- Cross-Site Scripting (XSS) – Reflected and Stored
- Cross-Site Request Forgery (CSRF)
- File Upload and Inclusion
- Broken Authentication
- Brute Force Attacks
- Security Misconfigurations
---
📘 Learning Outcomes
- Identified and exploited OWASP Top 10 vulnerabilities manually and with tools
- Built and configured a local vulnerable web application environment
- Practiced intercepting, modifying, and replaying HTTP requests with Burp Suite
- Created repeatable test scripts to automate scanning and exploitation
- Documented findings and steps taken during each attack scenario
---
⚠️ Legal Disclaimer
This project is for educational purposes only. Do not expose DVWA to the public internet.


### Run DVWA Using Docker:

```bash
git clone https://github.com/digininja/DVWA.git
cd DVWA
docker-compose up -d
