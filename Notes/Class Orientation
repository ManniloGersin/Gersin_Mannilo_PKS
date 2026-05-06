# 0-Class-Orientation.md

```md
# Class Orientation

## Introduction
Students are expected to introduce:
- Name
- Career Path
- Expectations from the course
- Working status or OJT experience

---

## Grading Breakdown
| Component | Percentage |
|---|---|
| Quizzes | 20% |
| Forum | 15% |
| Assignment | 15% |
| Project | 20% |
| Other Activities | 10% |
| Periodic Exam | 20% |

---

## Certification Pathway
Passing cybersecurity certifications may automatically give students a perfect score on related quizzes and exams.

### Certifications Mentioned
- ISC2 Certified in Cybersecurity
- CompTIA Security+
- Hack The Box Certifications
- TryHackMe Certificates
- TCM Security Certifications

---

## Forum Grades
Forum grades are based on:
- TryHackMe progress
- Hack The Box Academy rooms
- CyberDefenders activities

---

## Personal Knowledge System (PKS)
A PKS is a digital notebook system used to:
- Organize notes
- Connect ideas
- Store research
- Build a searchable knowledge base
```

---

# 1-Career-Opportunities-in-IT-Security.md

```md
# Career Opportunities in IT Security

## What is Cybersecurity?
Cybersecurity is the practice of protecting:
- Computer systems
- Networks
- Sensitive data

from:
- Theft
- Damage
- Unauthorized access

---

## Red Team vs Blue Team

### Red Team (Offensive Security)
Responsibilities:
- Simulate cyberattacks
- Find vulnerabilities
- Test defenses

### Blue Team (Defensive Security)
Responsibilities:
- Monitor networks
- Detect threats
- Implement defenses
- Improve security posture

---

## Career Opportunities
Cybersecurity offers:
- High demand
- Competitive salaries
- Remote work opportunities
- Strong career growth

---

## Common Cybersecurity Roles

### Vulnerability Assessor
- Finds system weaknesses
- Performs vulnerability scans

### Penetration Tester
- Conducts ethical hacking
- Performs proof-of-concept attacks

### Security Researcher
- Studies vulnerabilities and threats

### Web Application Penetration Tester
- Tests web application security

### SOC Analyst
- Monitors security events
- Responds to incidents

### Threat Hunter
- Searches for hidden threats

### DFIR Analyst
- Investigates cyber incidents
- Collects digital evidence

---

## Security Operations Center (SOC)
SOC responsibilities:
- Monitor security alerts
- Detect attacks
- Respond to incidents
- Maintain organizational security

---

## Three Pillars of Cybersecurity
1. People
2. Processes
3. Technology
```

---

# 2-Introduction-to-Security-Models.md

```md
# Introduction to Security Models and Threat Frameworks

## Assets
Anything valuable that must be protected.

### Tangible Assets
- Servers
- Laptops
- Networking equipment

### Intangible Assets
- Customer data
- Intellectual property
- Company reputation

---

## Vulnerabilities
Weaknesses in systems or processes.

### Technical Vulnerabilities
- Unpatched software
- Misconfigured firewalls
- Zero-day vulnerabilities

### Human Vulnerabilities
- Weak passwords
- Lack of training

---

## Threats
Anything capable of causing harm.

### Intentional Threats
- Hackers
- Ransomware groups
- Malicious insiders

### Accidental/Natural Threats
- Human error
- Floods
- Power outages

---

## Risk
Risk is the probability of a threat exploiting a vulnerability.

### Risk Formula
Risk = Threat × Vulnerability × Impact

---

## CIA Triad

### Confidentiality
Protecting data from unauthorized access.

### Integrity
Preventing unauthorized modification of data.

### Availability
Ensuring systems and data remain accessible.

---

## Confidentiality Controls
- Principle of Least Privilege (PoLP)
- Multi-Factor Authentication (MFA)
- Encryption
- Identity and Access Management (IAM)
```

---

# 3-The-Adversarial-Hook.md

```md
# The Adversarial Hook

## MITRE ATT&CK Framework
A framework that categorizes attacker behavior and tactics.

---

## Initial Access
Attackers attempt to gain an initial foothold in a system.

---

## Drive-by Compromise
A user becomes infected simply by visiting a malicious website.

### Common Methods
- Compromised websites
- Malvertising
- Cross-site scripting
- Malicious cloud-hosted scripts

---

## Fake CAPTCHA Campaign
Attackers trick users into:
1. Opening fake CAPTCHA pages
2. Running PowerShell commands
3. Downloading malware

### Techniques Used
- SEO poisoning
- Social engineering
- PowerShell abuse
- MSHTA abuse

---

## Command and Scripting Interpreter (T1059)
Attackers abuse scripting tools to execute malicious commands.

### Example
Invoke-Expression in PowerShell can execute commands directly.
```

---

# 4-Phishing-T1566.md

```md
# Initial Access (TA0001) – Phishing (T1566)

## Phishing
Attackers trick users into revealing sensitive information.

---

## Goal of Phishing
Gain initial access into a network through social engineering.

---

## Types of Phishing

### Spam
Mass unsolicited messages.

### Phishing
General credential theft attacks.

### Spear Phishing
Targets specific individuals or organizations.

### Whaling
Targets executives or high-profile victims.

### Smishing
Phishing through SMS/text messages.

### Vishing
Voice-call-based phishing attacks.

---

## Characteristics of Phishing Emails
- Fake sender addresses
- Urgent messages
- Suspicious links
- Malicious attachments

---

## Phishing and Confidentiality
Phishing attacks violate confidentiality by stealing credentials and private information.
```

---

# 5-Valid-Accounts-T1078.md

```md
# Initial Access (TA0001) – Valid Accounts (T1078)

## Valid Accounts
Attackers use stolen or legitimate credentials to access systems.

---

## Why Attackers Use Valid Accounts
Using real accounts:
- Bypasses security controls
- Avoids detection
- Provides persistent access

---

## Common Targets
- VPNs
- Remote Desktop
- Email systems
- Network devices

---

## Key Insight
Attackers often do not "hack in" — they simply log in using stolen credentials.

---

## Causes of Breaches
- Weak passwords
- Stolen credentials

---

## Defense in Depth
Using multiple layers of security protection.

### Examples
- MFA
- Password policies
- Monitoring
- Access controls
```

---

# 6-Exploit-Public-Facing-Application-T1190.md

```md
# Exploit Public-Facing Application (T1190)

## Public-Facing Applications
Systems accessible from the internet.

### Examples
- Web servers
- Email servers
- VPN gateways

---

## Exploitation
Attackers exploit vulnerabilities to gain access.

---

## Common Weaknesses
- Software bugs
- Zero-day vulnerabilities
- Misconfigurations

---

## Attack Lifecycle

### 1. Reconnaissance
Attackers identify vulnerable systems.

### 2. Exploitation
Malicious payloads are delivered.

### 3. Initial Access
Attackers gain shell access or remote execution.

---

## Shodan
A search engine used to identify internet-connected devices.

---

## Potential Results
- Remote Code Execution (RCE)
- Unauthorized access
- Data theft
```

---

# 7-Execution-T1059.md

```md
# Execution (TA0002) – Command and Scripting Interpreter (T1059)

## Execution
Execution allows attackers to run malicious code.

---

## Command and Scripting Interpreter
Attackers abuse legitimate scripting tools.

### Common Tools
- PowerShell
- CMD
- Bash
- Python
- JavaScript

---

## Living off the Land (LotL)
Attackers use built-in operating system tools instead of malware.

---

## Why Attackers Use This Technique
- Trusted by antivirus
- Legitimate administrative tools
- Harder to detect

---

## PowerShell Abuse
Attackers use PowerShell to:
- Download malware
- Execute encoded commands
- Run fileless malware

---

## JavaScript/VBScript Abuse
Scripts embedded in:
- Office files
- PDFs
- HTML files

can execute malicious code.
```

---

# 8-Persistence-TA0003.md

```md
# Persistence (TA0003)

## Persistence
Techniques used by attackers to maintain access after compromise.

---

## Why Persistence Matters
Without persistence:
- Access is lost after reboot
- Sessions terminate after logout

---

## Key Persistence Categories

### Account Manipulation
Creating or modifying accounts.

### Boot or Logon Auto-start
Programs execute during startup.

### Scheduled Tasks
Attackers automate malicious execution.

### Execution Flow Hijacking
Legitimate processes execute malicious code.

### Browser Extensions
Malicious browser add-ons maintain access.

---

## T1098 – Account Manipulation
Attackers modify accounts for long-term access.

---

## T1547 – Boot or Logon Autostart
Registry keys and startup folders execute malware automatically.

### Examples
- Run Keys
- Startup folders

---

## DLL Hijacking
Attackers abuse DLL loading mechanisms to run malicious code.
```

---

# 9-Discovery-TA0007.md

```md
# Discovery (TA0007)

## Discovery
Attackers gather information about systems and networks.

---

## Goals of Discovery
- Identify accounts
- Map the network
- Detect defenses
- Locate targets

---

## Discovery Categories

### Identity & Access
- Account discovery
- Permission groups
- Password policies

### Network & Infrastructure
- Network service discovery
- Cloud infrastructure discovery

### System State & Environment
- Process discovery
- Software discovery
- Virtual machine discovery

---

## T1046 – Network Service Discovery
Attackers scan for:
- Open ports
- Running services
- Vulnerable systems

### Common Tools
- Nmap
- Ping
- DNS queries

---

## T1087 – Account Discovery
Attackers enumerate:
- Local accounts
- Domain accounts
- Cloud accounts

---

## Evasion Techniques

### Debugger Evasion
Avoids analysis tools.

### Sandbox Evasion
Detects virtual environments to avoid detection.
```
