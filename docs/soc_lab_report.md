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
