# Execution (TA0002) – Command and Scripting Interpreter (T1059)

## What is Execution?
Execution is the tactic where attackers run malicious code on a local or remote system.

### Goals
- Deploy malware
- Control systems
- Steal data
- Move within a network

---

## Command and Scripting Interpreter (T1059)

Attackers abuse legitimate scripting and command-line tools to execute malicious commands.

### Common Tools
- PowerShell
- CMD
- Bash
- JavaScript
- Python

---

## Living off the Land (LotL)

Attackers use built-in system tools instead of custom malware to:
- Avoid detection
- Blend with normal activity
- Bypass antivirus software

---

## T1059.001 – PowerShell

PowerShell is heavily abused in Windows environments.

### Common Malicious Uses
- Downloading malware
- Running encoded commands
- Fileless malware execution
- Remote administration

---

## Encoded Commands

Attackers use Base64 encoded commands to:
- Hide malicious activity
- Bypass detection
- Obfuscate payloads

---

## T1059.007 – JavaScript / VBScript

Scripts inside:
- HTML files
- PDFs
- Office documents

can execute malicious code and download malware.

---

## GootLoader Malware

GootLoader is a JavaScript malware loader often spread through SEO poisoning and malicious websites.

---

## Detection & Mitigation

### Detection
- Suspicious PowerShell activity
- Encoded commands
- Unusual script execution

### Mitigation
- Enable PowerShell logging
- Restrict script execution
- Monitor command-line activity
- Keep systems updated

---

## Key Takeaways
- T1059 uses trusted system tools for malicious execution.
- PowerShell is one of the most abused tools.
- Living off the Land techniques are difficult to detect.
