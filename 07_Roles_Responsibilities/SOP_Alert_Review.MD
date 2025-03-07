# SOC Standard Operating Procedures (SOPs)

## **Overview**
This document outlines **Security Operations Center (SOC) Standard Operating Procedures (SOPs)** to ensure efficient and standardized handling of security incidents. These SOPs follow **NIST 800-61, ISO/IEC 27035, and MITRE ATT&CK** best practices.

## **1. General SOC Procedures**
SOC procedures define the **framework for managing security events, escalations, and incident resolution.**

### **1.1 SOC Workflow Overview**
1. **Threat Detection** → Alerts triggered via SIEM, EDR, IDS/IPS.
2. **Alert Triage** → Initial review to determine severity.
3. **Investigation & Analysis** → Deep dive into logs, threat intelligence, and forensic evidence.
4. **Incident Containment** → Immediate action to mitigate damage.
5. **Response & Remediation** → Root cause analysis, patching, policy updates.
6. **Post-Incident Review** → Lessons learned, documentation, and continuous improvement.

---

## **2. SOP: Security Alert Review**

### **2.1 Purpose**
This SOP outlines the **step-by-step process** for reviewing security alerts in the SOC, ensuring accurate classification, escalation, and response.

### **2.2 Scope**
- Applies to **SOC Analysts, Incident Responders, and Threat Hunters**.
- Covers alerts from **SIEM (Splunk, ELK), EDR (CrowdStrike, SentinelOne), and IDS/IPS**.
- Ensures compliance with **ISO/IEC 27035 and NIST 800-61**.

### **2.3 Roles & Responsibilities**
| **Role** | **Responsibility** |
|---------|------------------|
| **SOC Analyst (L1)** | Initial triage, basic analysis, false positive reduction. |
| **SOC Investigator (L2)** | In-depth investigation, root cause analysis, containment. |
| **Incident Responder (L3)** | Active threat response, system isolation, remediation. |
| **SOC Manager** | Escalation oversight, reporting, continuous improvement. |

### **2.4 Alert Review Workflow**

#### **Step 1: Initial Alert Review**
✅ **Check alert details** in SIEM/EDR (source, destination, timestamp).  
✅ **Correlate with threat intelligence** feeds (MITRE ATT&CK, VirusTotal, internal IOC lists).  
✅ **Classify alert** (Low, Medium, High, Critical).  

#### **Step 2: Validate False Positives**
✅ **Check past occurrences** → Has this alert appeared before?  
✅ **Analyze normal behavior** → Compare against baselines.  
✅ **Run additional threat queries** in Splunk, CrowdStrike, or ELK.

#### **Step 3: Investigate Potential Threats**
✅ **Gather forensic evidence** → Review logs, network traffic, process execution data.  
✅ **Map activity to MITRE ATT&CK** tactics and techniques.  
✅ **Engage Threat Hunting** → Look for associated IOCs.

#### **Step 4: Escalation Decision**
✅ **Low severity** → Document, close alert if benign.  
✅ **Medium severity** → Flag for continuous monitoring.  
✅ **High severity** → Escalate to Incident Response (IR) team.  
✅ **Critical severity** → Immediate containment, engage SOC Manager & Executive Team.

#### **Step 5: Containment & Remediation**
✅ **Contain affected hosts** (Isolate endpoints, disable accounts).  
✅ **Apply security patches** if applicable.  
✅ **Strengthen detection rules** to prevent recurrence.

#### **Step 6: Documentation & Lessons Learned**
✅ **Update incident records** in ITSM (ServiceNow, Jira).  
✅ **Conduct post-mortem analysis** for major incidents.  
✅ **Refine SOC playbooks & alert tuning.**

---

## **3. SOP Best Practices**
✅ **Standardize Alert Classification:** Ensure consistent severity ratings across teams.  
✅ **Automate False Positive Reduction:** Use AI/ML to minimize noise.  
✅ **Conduct Continuous SOC Training:** Keep analysts updated on evolving threats.  
✅ **Integrate with ITSM:** Ensure smooth incident tracking and escalation.  
✅ **Align with Security Frameworks:** NIST, MITRE ATT&CK, CIS Controls.