# SOC Lab Report (Markdown)
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

| Screenshot | Description | Tool | Timestamp |
|------------|-------------|------|-----------|
| task1_ssh_install.png | SSH service installed and verified via `ss -tulnp` | systemctl, ss | 13:44 |
| task2_ssh_login.png   | SSH login attempt with password rejection | ssh | 13:44 |
| task3_ps_aux.png      | Process list showing active services | ps aux | 13:41 |
| task4_process_list.png| Extended process list with kernel threads | ps aux | 13:48 |
| task5_system_monitor.png | System monitoring with resource usage | ps aux | 15:41 |
| task6_evidence.png    | Evidence capture for SOC lab | ps aux | 15:38 |
## 7. Outcomes
- Attack contained successfully
- Incident escalated and documented
- Evidence preserved for review

## 8. Recommendations
- Patch vulnerable services
- Continuous monitoring with Wazuh rules
- Automated blocking with CrowdSec
- Structured escalation workflows with TheHive

## 9. Conclusion
- Summary of SOC workflow effectiveness
- Lessons learned
- Next steps for improvement
