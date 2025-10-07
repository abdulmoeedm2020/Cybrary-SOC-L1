# Cybrary-SOC-L1

╔══════════════════════════════════════════════════════════╗
║   CYBRARY // SOC ANALYST LEVEL 1                        ║
║──────────────────────────────────────────────────────────║
║  ▸ Real-World Blue Team Skills                          ║
║  ▸ SIEM • Log Analysis • Threat Hunting • Triage         ║
║  ▸ Incident Response • Malware Indicators • Escalation   ║
╚══════════════════════════════════════════════════════════╝
       🧩 "Detect · Analyze · Respond · Repeat"

---

## 📘 **Overview**
A practical roadmap and lab-driven collection to learn the fundamentals required for a **Security Operations Center (SOC) Level 1 Analyst** role — built to mirror **Cybrary's SOC-L1** course structure:  
focus on log monitoring, alert triage, basic incident response, and SIEM fundamentals.

---

## 🎯 **Learning Objectives**

- Understand SOC roles & shift handoffs (L1 responsibilities).  
- Read and interpret common security logs (Windows, Linux, firewall, proxy).  
- Use a SIEM for alert investigation and triage.  
- Apply basic threat-hunting queries and create simple detection rules.  
- Perform initial containment & escalate to L2/L3 with detailed notes.  
- Get hands-on with: **Splunk/ELK, Wireshark, Sysinternals, PowerShell, and Python**.

---

## 🧭 **Who This Is For**

- 🧑‍💻 Beginners aiming for a **SOC L1 Analyst** position.  
- 🎓 Students converting **Cybrary course knowledge** into practical labs.  
- 💼 Entry-level cybersecurity aspirants building a **blue-team portfolio**.

---

## 🔁 **Prerequisites**

- Basic **Windows/Linux OS** knowledge.  
- Understanding of **TCP/IP, DNS, and common ports**.  
- Familiarity with log reading and command-line usage.  

---

## 🗂️ **Suggested Modules / Syllabus**

| Module | Topics | Lab Idea |
|--------|---------|----------|
| **1. Intro to SOC & L1** | Roles, responsibilities, shift model | Create a mock shift handover template |
| **2. Log Sources & Formats** | Windows Event, Syslog, Firewall logs | Collect & parse Windows Security logs |
| **3. SIEM Fundamentals** | Ingestion, correlation, dashboards | Set up ELK or Splunk Free, build dashboard |
| **4. Alert Triage & Investigation** | False positives, IOC enrichment | Triage a phishing alert, document actions |
| **5. Network Traffic Basics** | Packets, anomalies, protocols | Capture traffic in Wireshark and analyze |
| **6. Endpoint Triage** | Processes, scheduled tasks, autoruns | Use Sysinternals Process Explorer |
| **7. Threat Intelligence & Enrichment** | IOC lookups, automation | Automate enrichment (VirusTotal, OTX) |
| **8. Incident Handling & Escalation** | Playbooks, containment | Create incident report + evidence list |
| **9. Reporting & Communication** | Note writing, lessons learned | Draft escalation for ransomware alert |

---

## 🛠️ **Tools & Technologies**

- **SIEM:** Splunk (Free), ELK Stack (Elastic).  
- **Log Collection:** Winlogbeat, Filebeat, NXLog.  
- **Network Analysis:** Wireshark, tcpdump.  
- **Endpoint Triage:** Sysinternals Suite, lsof/ss/top.  
- **Scripting:** Python & PowerShell.  
- **Threat Intel:** VirusTotal, AlienVault OTX, AbuseIPDB.  

---

## 🧪 **Hands-on Lab Ideas**

- 🧩 Build a mini-SIEM: Ingest Windows logs → Detect failed RDP brute-force attempts.  
- 🧩 Analyze a phishing email: extract headers, links, and attachments.  
- 🧩 Perform pcap triage: identify C2 beacons in Wireshark.  
- 🧩 Run host triage: list processes, network sockets, and autoruns.  

---

## ✅ **L1 Daily Playbook Checklist**

1. Review overnight/high-priority alerts.  
2. Enrich and verify IOCs (IPs/domains/hashes).  
3. Check affected systems or request snapshots.  
4. Isolate hosts when required.  
5. Escalate confirmed incidents to L2/L3.  
6. Document all actions and update dashboards.  

---

## 💼 **Typical SOC L1 Responsibilities**

- Monitor alerts from SIEM and detection systems.  
- Perform triage and initial investigation.  
- Escalate verified incidents with evidence.  
- Follow playbooks/runbooks for standard incidents.  
- Update documentation and assist with tuning detection rules.  

---

## 📝 **Sample Resume Bullets**

- Investigated **50+ daily SIEM alerts**, reducing false positives by 30%.  
- Conducted **host triage** using Sysinternals and Wireshark.  
- Authored **playbooks** for phishing and ransomware investigations.  

---

## ❓ **Common Interview Questions**

**Q:** How do you triage a phishing alert?  
**A:** Verify sender and headers, analyze URLs, isolate affected accounts, and escalate with evidence.  

**Q:** What’s your first step for ransomware indicators?  
**A:** Isolate host, capture logs/memory, and escalate to L2 immediately.  

**Q:** How can you reduce false positives?  
**A:** Tune rules, normalize logs, and add asset or user context enrichment.  

---

## 📦 **Repository Structure**



