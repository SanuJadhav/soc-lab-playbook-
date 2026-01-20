# soc-lab-playbook-
SOC Lab Report including advanced log analysis, threat intelligence integration, incident escalation workflows, and capstone attack simulation
# SOC Lab Playbook & Report

## 🛠 Tools Used
- Kali Linux
- Elastic Security
- Wazuh
- TheHive
- CrowdSec
- Velociraptor
- Metasploit

## 📂 Repository Structure
- `docs/` → Full SOC lab report (PDF + Markdown)
- `theoretical_knowledge.md` → Core SOC concepts
- `practical_application.md` → Hands-on exercises
- `playbooks/` → Automation workflows (SOAR, Splunk Phantom)
- `screenshots/` → Evidence and dashboards

## ✅ Objectives
- Demonstrate SOC workflows from detection to response
- Document evidence with integrity
- Provide reproducible playbook steps for analysts

## 📌 Recommendations
- Regular patching of vulnerable services
- Continuous monitoring with Wazuh rules
- Automated IP blocking with CrowdSec
- Structured escalation using TheHive
## 📊 Executive Summary
This SOC lab demonstrates end‑to‑end detection, response, and escalation workflows against a simulated Samba exploit.  

- **Detection:** Wazuh identified suspicious activity in system logs  
- **Response:** CrowdSec automatically blocked the attacker’s IP  
- **Escalation:** TheHive escalated the case to Tier 2 analysts  
- **Evidence:** Velociraptor preserved forensic artifacts with SHA‑256 integrity checks  

**Outcome:** SOC workflows effectively contained and documented the attack, strengthening organizational resilience.
