# Security Tools, so hot right now.

> Better understanding of what tools & methods are used in SOC environments.
> Labs, guided modules, CTF exercises, & practical examples across various platforms.
> Although a lot of my focus is in support/sales engineering, I'm fascinated in how cybersecurity tools are used!

---

## 🔍 Overview


The structure includes:
- 🧠 **HTB Academy** – Linux, Windows, Bash, Networking, Nmap, etc.
- 💻 **HTB Machines** – Starting Point & beyond write-ups
- 🧩 **TryHackMe** – room walk-throughs, flags, and tool usage
- 📚 **Cybrary** – Various platform milestones, notes, and practicals

---

## 📂 Repo Structure

SOC-Path/  
├── HTB_Academy/              # Notes and labs from HTB Academy  
│   ├── Linux_Fundamentals.md  
│   └── screenshots/  
├── HTB_Machines/             # Write-ups from Hack The Box machines  
│   ├── Starting_Point.md  
│   └── screenshots/  
├── TryHackMe/                # Room-based exercises  
├── Cybrary/  
│   ├── Certificates/             # Downloaded Cybrary completion certs (PDF)  
│   ├── SIEM_Search_Exp/          # Screenshot series from Wazuh SIEM search challenge  
│   ├── Windows_Event_Logs/       # Screenshots from Windows Event Log analysis and Wazuh filtering  
│   ├── Log_Analysis/             # Screenshot sequence of Cybrary’s log filtering challenge  
│   ├── The_Hive/                 # Security ticketing workflows in TheHive  
│   └── Wazuh/                    # MITRE ATT&CK detections, rule filters, and dashboard visuals  
└── README.md  

---

## 📜 Certificates

- [SIEM Basics](Cybrary/Certificates/cybrary-cert-siem-basics.pdf)  
- [Search Expressions in a SIEM](Cybrary/Certificates/cybrary-cert-search-expressions-in-a-siem.pdf)  
- [Log Analysis Basics](Cybrary/Certificates/cybrary-cert-log-analysis-basics.pdf)  
- [Security Ticketing Basics](Cybrary/Certificates/cybrary-cert-security-ticketing-basics.pdf)  
- [Windows Event Logs Basics](Cybrary/Certificates/cybrary-cert-windows-event-logs-basics.pdf)  

---

## 🧰 Tools Covered So Far

**Defensive Monitoring:**  
Splunk, Zeek, Suricata, Wazuh, Graylog, tcpdump, Wireshark, OpenVAS, Lynis, Fail2ban, TheHive, Security Onion

**Offensive Tools:**  
Metasploit, Hydra, Nmap, Burp Suite

**OSINT & Reconnaissance:**  
Recon-ng, Shodan, TheHarvester

**Scripting & Automation:**  
Bash, PowerShell, Python, YAML, JSON, Ansible, Docker

**Frameworks & Concepts:**  
MITRE ATT&CK, log analysis, IDS/IPS, ticketing workflows, SIEM, SSH, firewalls, UFW, syslog, DNS/DHCP, VLANs, NAT

---

## 🔍 Notable Screens (from Labs)

**TheHive Ticket Lifecycle:**  
![Ticket Created](Cybrary/TheHive/thehive_ticket_created_details.png)  
![Ticket Closed](Cybrary/TheHive/thehive_ticket_closed_summary.png)

**Wazuh MITRE Rule Detection (T1098):**  
![MITRE Detection](Cybrary/Wazuh/wazuh_mitre_t1098_pikachu_details.png)

**Windows Event Log Analysis:**  
![Pikachu Account Created](Cybrary/Windows_Event_Logs/event_log_4720_pikachu_generalview.png)

---

## 🧠 Goal
Showcasing tools, detection, response, & application. This includes:  
- Modules from HTB Academy, TryHackMe, & Cybrary  
- Practicing ticketing & detection tools using platforms like TheHive & Wazuh  
- Capturing screenshots, answering questions, & showing methodology  

---

**Maintained by [flipxcrsp](https://github.com/flipxcrsp)**  
*“The grind, one lab at a time.”*
