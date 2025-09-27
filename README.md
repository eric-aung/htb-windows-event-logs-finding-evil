# htb-windows-event-logs-finding-evil
Writeup and analysis of the Windows Event Logs &amp; Finding Evil module from HackTheBox Academy - demonstrating SOC investigation, Sysmon log analysis, and Windows attack detection techniques
🔍 About This Project
This repository contains my writeup and analysis for the **Windows Event Logs & Finding Evil** lab from HackTheBox Academy.

The module simulates real-world attacker techniques (DLL hijacking, unmanaged PowerShell injection, LSASS credential dumping, and PPID spoofing), and challenges you to detect them by analyzing Windows event logs and Sysmon telemetry.

### Why this matters
- Shows ability to **detect malicious activity** using native Windows logs, Sysmon, and ETW.
- Demonstrates **SOC analyst workflow**: filtering, correlating, and interpreting logs to answer investigation questions.
- Highlights practical knowledge of **blue-team detection** and **incident response skills**.
- Builds a foundation for **SIEM use cases** (Splunk, Sentinel, ELK) by applying event filtering and threat hunting logic.

### Key Skills Demonstrated
- Event log analysis (`Get-WinEvent`, Sysmon Event IDs 1, 7, 10)
- Detecting credential dumping and process injection
- Investigating parent-child process anomalies (PPID spoofing)
- Writing clear technical documentation for security investigations
