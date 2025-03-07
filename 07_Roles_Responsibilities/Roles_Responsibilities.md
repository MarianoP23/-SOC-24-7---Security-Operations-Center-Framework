# SOC Roles and Functions

## **Overview**
A **Security Operations Center (SOC)** is composed of multiple roles that work together to detect, analyze, respond to, and prevent cybersecurity threats. Each role has distinct responsibilities that contribute to an organization's security posture. This document defines the key SOC roles, their functions, and responsibilities, aligning with **NIST 800-61, ISO/IEC 27035, and MITRE ATT&CK** best practices.

---

## **1. SOC Team Structure**
SOC teams are generally categorized into **three tiers** based on expertise level and responsibilities:

| **Tier** | **Function** | **Key Responsibilities** |
|---------|-------------|-------------------------|
| **Tier 1 - SOC Analyst (L1)** | Alert Triage & Initial Investigation | Monitor security alerts, validate incidents, escalate threats. |
| **Tier 2 - SOC Investigator (L2)** | Threat Investigation & Response | Conduct forensic analysis, hunt threats, contain and remediate incidents. |
| **Tier 3 - SOC Engineer / Threat Hunter (L3)** | Threat Intelligence & Advanced Detection | Develop security rules, maintain SIEM, perform deep-dive investigations. |
| **SOC Manager** | SOC Operations & Oversight | Oversee SOC activities, coordinate response efforts, ensure compliance. |
| **CISO / Security Director** | Executive Security Leadership | Define security strategy, risk management, and compliance oversight. |

---

## **2. Key SOC Roles and Responsibilities**

### **2.1 SOC Analyst (L1)** - *Entry-Level Security Analyst*
**Function:** First line of defense, responsible for monitoring security events and alerts.

**Responsibilities:**
- Monitor **SIEM dashboards** for real-time alerts.
- **Triage security incidents** to determine severity.
- **Escalate threats** to Tier 2 for deeper investigation.
- Document findings and create initial **incident reports**.
- Identify **false positives** and fine-tune alert rules.

**Required Skills:**
✔ Basic knowledge of **SIEM tools (Splunk, ELK)**  
✔ Understanding of **MITRE ATT&CK framework**  
✔ Familiarity with **network and endpoint security**  

---

### **2.2 SOC Investigator (L2)** - *Incident Responder*
**Function:** Investigates security incidents and coordinates response actions.

**Responsibilities:**
- Conduct **forensic analysis** on compromised systems.
- Perform **deep-dive investigations** using threat intelligence sources.
- **Contain security incidents** (e.g., isolate infected hosts, disable accounts).
- Work with **Threat Hunting teams** to identify attack patterns.
- Coordinate **remediation efforts** with IT and Security teams.

**Required Skills:**
✔ Expertise in **digital forensics and incident response (DFIR)**  
✔ Hands-on experience with **endpoint detection (CrowdStrike, SentinelOne)**  
✔ Knowledge of **malware analysis and reverse engineering**  

---

### **2.3 Threat Hunter (L3)** - *Proactive Threat Detection Specialist*
**Function:** Proactively searches for hidden threats that evade traditional defenses.

**Responsibilities:**
- Develop **custom threat hunting queries** (Splunk, CrowdStrike, Elastic).
- Analyze **network traffic** for suspicious activity.
- Identify **Indicators of Compromise (IOCs)** and **Indicators of Attack (IOAs)**.
- Implement **adversary emulation** based on **MITRE ATT&CK** tactics.
- Work with security engineers to **improve detection rules**.

**Required Skills:**
✔ Deep knowledge of **cyber threat intelligence (CTI)**  
✔ Familiarity with **attack simulation tools (Atomic Red Team, CALDERA)**  
✔ Experience in **behavioral analytics & anomaly detection**  

---

### **2.4 SOC Engineer** - *SIEM & Security Tool Expert*
**Function:** Maintains SOC infrastructure, ensuring security tools are optimized.

**Responsibilities:**
- Deploy and configure **SIEM, SOAR, EDR, and IDS/IPS**.
- Automate **incident response playbooks**.
- Develop **detection rules and alert tuning**.
- Integrate **Threat Intelligence Platforms (TIPs)** into SOC workflows.
- Maintain compliance with **NIST 800-61 & ISO 27035**.

**Required Skills:**
✔ Advanced **SIEM (Splunk, ELK, QRadar) & SOAR automation**  
✔ Proficiency in **scripting (Python, PowerShell, Ansible)**  
✔ Experience with **log correlation & rule tuning**  

---

### **2.5 SOC Manager** - *Operations & Oversight*
**Function:** Oversees the SOC team, ensuring smooth operations and continuous improvement.

**Responsibilities:**
- Develop and enforce **SOC policies & procedures**.
- Ensure alignment with **compliance standards (ISO 27001, GDPR, PCI DSS).**
- Monitor **SOC performance metrics (MTTD, MTTR, false positive rate).**
- Manage **SOC staffing, budget, and vendor relationships**.
- Serve as **primary incident escalation point**.

**Required Skills:**
✔ Leadership in **SOC operations & risk management**  
✔ Experience with **compliance frameworks & audit processes**  
✔ Strong background in **incident response & crisis management**  

---

### **2.6 CISO (Chief Information Security Officer)** - *Executive Security Leadership*
**Function:** Defines the organization's cybersecurity strategy and risk management.

**Responsibilities:**
- Develop **enterprise security policies & frameworks**.
- Oversee **risk management & threat intelligence programs**.
- Ensure compliance with **industry regulations (NIST, ISO, GDPR, PCI DSS).**
- Work with executive leadership on **budgeting & security investments**.
- Lead security awareness and training programs.

**Required Skills:**
✔ Executive-level **risk & governance expertise**  
✔ Strategic **cybersecurity planning & leadership**  
✔ Strong understanding of **compliance, regulatory requirements, and business risk**  

---

## **3. SOC Role Progression & Career Path**
A SOC career typically follows this **progression path:**

| **Entry Level** | **Mid-Level** | **Advanced** |
|---------------|------------|-------------|
| SOC Analyst (L1) | SOC Investigator (L2) | SOC Engineer (L3) |
| Security Analyst | Incident Responder | Threat Hunter |
| IT Support (Cybersecurity Focus) | SOC Manager | CISO / Security Director |

### **SOC Skill Development Roadmap:**
✔ **Technical Skills:** SIEM, SOAR, EDR, forensic analysis, scripting (Python, PowerShell).  
✔ **Analytical Skills:** Threat intelligence, log analysis, adversary simulation.  
✔ **Management Skills:** Leadership, compliance, security program development.  

---
