# Windows-Terminal-Hardening

[![VirusTotal Scan](https://github.com/simeononsecurity/Windows-Terminal-Hardening/actions/workflows/virustotal.yml/badge.svg)](https://github.com/simeononsecurity/Windows-Terminal-Hardening/actions/workflows/virustotal.yml)

Windows-Terminal-Hardening is a PowerShell script that elevates privileges and performs various Windows hardening tasks to enhance security. The script requires administrative rights to run and performs the following actions: disabling CMD and PowerShell v2, setting PowerShell Constrained Language Mode, enabling PowerShell logging, removing WSMan listeners, disabling the WSMan Service, and disabling the firewall rule for Windows Remote Management. The script outputs a message confirming the elevation of privileges.

## What does this script do?
- Disables Command Prompt
- Disables PowerShell v2
- Disables WSMAN and PSRemoting
- Enables PowerShell Constrained Language Mode
- Enables PowerShell Logging

## Recommended Reading:
- [PowerShell Best Practices](https://www.digitalshadows.com/blog-and-research/powershell-security-best-practices/)
- [PowerShell Constrained Language Mode](https://devblogs.microsoft.com/powershell/powershell-constrained-language-mode/)
- [Securing PowerShell in the Enterprise](https://www.cyber.gov.au/acsc/view-all-content/publications/securing-powershell-enterprise)
- [Windows Defender Hardening](https://github.com/simeononsecurity/Windows-Defender-Hardening)

## Download the required files:

Download the required files from the [GitHub Repository](https://github.com/simeononsecurity/Windows-Terminal-Hardening)

## How to run the script:

**The script may be lauched from the extracted GitHub download like this:**
```
.\sos-windowsterminalhardening.ps1
```
