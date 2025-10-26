# Cybersecurity-Homelab-SIEM-Detection-Setup
## Purpose:
Configured Wazuh SIEM and endpoint monitoring across Linux and Windows VMs, continuing from Cybersecurity Homelab: Building the Environment. Set up alerts for SSH authentication failures, WinRM logins, and sensitive file modifications to simulate real-world attack detection and response within a controlled lab environment. The next installment is Cybersecurity Homelab: Vulnerability & Attack Simulation.

## Implementation:
- Configured Wazuh SIEM on Security Server 2, integrating Linux and Windows agents.
- Deployed insecure services (SSH, WinRM, RDP) across lab VMs to simulate common vulnerabilities.
- Created and monitored sensitive files for File Integrity Monitoring (FIM) exercises.
- Built detection and alerting workflows for failed SSH logins, successful WinRM logons, and file modifications.
- Documented all configurations, rules, monitors, and alerts with screenshots for reproducibility and lab-based testing.

## Skills Demonstrated:
- **SIEM Setup & Management** – Configured Wazuh, created monitors, triggers, and alerts for Windows and Linux endpoints.
- **Vulnerability Simulation** – Deployed insecure SSH, WinRM, and RDP for detection testing.
- **File Integrity Monitoring** – Monitored sensitive file changes with syscheck and custom rules.
- **Log Collection & Analysis** – Collected and analyzed endpoint logs to detect suspicious activity.
- **Alerting & Monitoring** – Designed alert workflows for failed logins, successful logons, and file access.
- **Scripting & Automation** – Developed Bash, Python, and PowerShell scripts for monitoring tasks.
- **Firewall & Endpoint Security** – Managed service access and firewall rules to emulate exposures.
- **Documentation & Reproducibility** – Created step-by-step guides with screenshots for repeatable labs.
- **Problem Solving** – Troubleshot agent deployment, log parsing, and monitor configurations across OSes.

## Deployed Vulnerabilities:
<img width="867" height="587" alt="image" src="https://github.com/user-attachments/assets/b8f4c63b-4d5d-4da0-8cac-ac8b61c9d0bb" />

## Prerequisites & Dependencies:
Refer to Cybersecurity-Homelab-Building-The-Environment readme.

## Documentation/Step By Step Guide:
Full step-by-step setup and configuration instructions are provided in the accompanying PDF file.  
[Here Is The Link](Cybersecurity-Homelab-SIEM-&-Detection-Setup%20Documentation.pdf)

## Credits:

- Developed by Nathan Sinclair, inspired by Grant Collins’ Build a Cybersecurity Homelab: Enterprise 101 (https://projectsecurity.teachable.com/p/build-a-cybersecurity-homelab-a-practical-guide-to-offense-defense-enterprise-101). Special thanks to Grant Collins for creating such a valuable learning resource. 

- Tools used include Wazuh, Security Onion, MailHog, VirtualBox, and Windows/Ubuntu OSs. 

- Documentation and content suggestions assisted by ChatGPT and other large language models (LLMs), with thanks to the open-source communities behind the tools. 
