# SOC Lab Report

## 1. Introduction
- Purpose of the SOC lab
- Scope of the simulation
- Tools and environment used

## 2. Lab Environment
- Kali Linux setup
- SOC tools installed (Wazuh, Elastic, TheHive, CrowdSec, Velociraptor, Metasploit)
- Network topology and vulnerable services

## 3. Attack Simulation
- Exploit scenario: Samba vulnerability
- Steps taken with Metasploit
- Expected vs. observed behavior

## 4. Detection
- Wazuh alerts triggered
- Elastic dashboards visualization
- IOC identification

## 5. Response
- CrowdSec automated IP blocking  
- Manual triage and escalation  
- Case creation in TheHive  

## 6. Evidence Preservation
- Velociraptor forensic collection  
- SHA-256 hashing for integrity  
- Chain of custody documentation  

## 📸 Screenshot Index

| Screenshot              | Description                                   | Tool     | Timestamp |
|-------------------------|-----------------------------------------------|----------|-----------|
| task1_ssh_install.png   | SSH service installed and verified via `ss -tulnp` | systemctl, ss | 13:44 |
| task2_ssh_login.png     | SSH login attempt with password rejection     | ssh      | 13:44 |
| task3_ps_aux.png        | Process list showing active services          | ps aux   | 13:41 |
| task4_process_list.png  | Extended process list with kernel threads     | ps aux   | 13:48 |
| task5_system_monitor.png| System monitoring with resource usage         | ps aux   | 15:41 |
| task6_evidence.png      | Evidence capture for SOC lab                  | ps aux   | 15:38 |

## 7. Outcomes
- Attack contained successfully  
- Incident escalated and documented  
- Evidence preserved for review  

## 8. Recommendations

### Technical Hardening
- Patch vulnerable Samba service and keep packages updated.
- Enforce strong authentication (disable password login, enable SSH keys).
- Apply least privilege principles for user accounts and services.

### Monitoring & Detection
- Expand Wazuh rules to cover privilege escalation attempts and suspicious process activity.
- Integrate Elastic dashboards with threat intelligence feeds for real‑time IOC correlation.
- Schedule periodic log reviews and anomaly detection.

### Response & Escalation
- Automate IP blocking with CrowdSec for critical alerts.
- Standardize escalation workflows in TheHive with severity tiers.
- Maintain playbooks for common attack scenarios to reduce response time.

### Evidence & Audit
- Continue using Velociraptor for forensic collection with SHA‑256 integrity checks.
- Document chain of custody for all evidence in lab and production environments.
- Store screenshots and artifacts in structured folders with timestamps.

### Organizational Resilience
- Conduct regular SOC simulations to test detection and response workflows.
- Train Tier 1 analysts on triage best practices.
- Review lessons learned after each incident and update playbooks accordingly.

## 9. Conclusion
The SOC lab demonstrated effective detection, response, escalation, and evidence preservation workflows.  
Screenshots and forensic artifacts validate each stage of the process.  
With the recommended improvements, the SOC environment will be more resilient, faster in response, and better prepared for real‑world incidents.
