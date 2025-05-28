# SOC Lab Simulation Project 01

## 🔒 Overview
This project simulates a beginner-level SOC (Security Operations Center) analyst workflow. It includes system log collection, simulated attacks, detection using basic tools, and a mini incident response report.

## 🎯 Objectives
- Collect logs from a Linux/Windows test machine.
- Simulate attacks (failed SSH logins, nmap scan, brute-force).
- Analyze logs using Wireshark and Splunk.
- Write an incident report on the findings.

## 🧰 Tools Used
- Kali Linux
- Wireshark
- Splunk (Free Tier)
- Nmap
- SSH server
- VirtualBox/VMware

## ⚙️ Steps Performed

1. **Setup & Logging**
   - Configured SSH on Linux.
   - Enabled logging.
   - Installed and configured Splunk to receive logs.

2. **Attack Simulation**
   - Performed failed SSH login attempts.
   - Conducted a port scan using `nmap`.
   - Tried a basic brute-force with `hydra`.

3. **Analysis**
   - Captured packets with Wireshark.
   - Detected malicious behavior in logs.
   - Created dashboards in Splunk (screenshots included).

4. **Response**
   - Documented how to block IPs, notify users, and clean systems.

## 📝 Sample Output

> Screenshot folder: `outputs/screenshots/`
> Log files: `outputs/logs/`
> Report PDF: `incident_report.pdf`
![Failed SSH Attempts](outputs/screenshots/failed_ssh_attempts.png)  
_Figure 1: Screenshot showing multiple failed SSH login attempts as captured in logs._

## 🚀 Next Steps
- Automate with bash or Python in future versions.
- Integrate more tools (Wazuh, Suricata, ELK).

