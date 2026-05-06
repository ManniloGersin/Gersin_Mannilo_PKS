# The Adversarial Hook: Understanding Initial Access and Exploitation
- Built into Windows
- Trusted by the operating system
- Powerful for automation

### Common Malicious Uses
- Downloading malware
- Running encoded commands
- Fileless malware execution
- Remote command execution

---

## Invoke-Expression
`Invoke-Expression` is a PowerShell cmdlet that executes strings as commands.

### Security Risk
Attackers use it to:
- Execute hidden payloads
- Run downloaded scripts
- Bypass simple security checks

---

## Key Takeaways
- Attackers often rely on human interaction.
- Initial Access is the first major stage of compromise.
- PowerShell and scripting tools are commonly abused.
- Social engineering remains highly effective.
- The MITRE ATT&CK Framework helps defenders understand attacker behavior.
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
