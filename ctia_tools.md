# CTIA v2 Tools Guide

## Module 1: Threat Intelligence Concepts

### Tools
- MISP
- OpenCTI
- ThreatConnect
- Anomali

### Purpose
- Collect threat intelligence
- Share intelligence with teams
- Manage Indicators of Compromise (IOCs)
- Correlate threat data

---

## Module 2: Cyber Threats and Threat Actors

### Frameworks and Resources
- MITRE ATT&CK
- CVE Database
- NIST
- FIRST

### Purpose
- Study threat actors
- Understand attack techniques
- Map attacker behavior (TTPs)

---

## Module 3: Requirements, Planning, and Direction

### Tools
- Microsoft Excel
- Ticketing Systems
- Project Management Tools

### Purpose
- Define intelligence requirements
- Plan intelligence collection
- Track intelligence activities

---

## Module 4: Data Collection and Processing

### Search and Google Dorking

#### Tools
- Google Search
- Google Hacking Database (GHDB)

#### Purpose
- Find exposed information
- Discover public documents
- Identify potential security risks

### Domain Intelligence

#### Tools
- WHOIS
- DNSDumpster
- MXToolbox
- ViewDNS

#### Purpose
- Gather domain information
- Find DNS records
- Discover subdomains

### Internet Exposure Intelligence

#### Tools
- Shodan
- Censys
- Netcraft

#### Purpose
- Identify internet-facing assets
- Find open ports and services
- Analyze exposed systems

### OSINT Automation

#### Tools
- SpiderFoot
- Maltego

#### Purpose
- Automate intelligence gathering
- Visualize relationships
- Perform link analysis

### Social Media Intelligence (SOCMINT)

#### Tools
- Maltego
- Social Searcher

#### Purpose
- Investigate social media profiles
- Gather public information
- Profile threat actors

---

## Module 5: Data Analysis

### IOC Analysis

#### Tools
- VirusTotal
- URLVoid
- IPVoid

#### Purpose
- Check IP reputation
- Analyze URLs
- Investigate suspicious files

### Malware Analysis

#### Tools
- Any.Run
- Hybrid Analysis
- Joe Sandbox

#### Purpose
- Analyze malware behavior
- Identify indicators
- Study malware activity

### Network Analysis

#### Tools
- Wireshark
- tcpdump

#### Purpose
- Capture network traffic
- Analyze packets
- Investigate network incidents

---

## Module 6: Intelligence Dissemination

### Tools
- Microsoft Word
- Microsoft PowerPoint
- Microsoft Excel
- Reporting Dashboards

### Purpose
- Create intelligence reports
- Present findings
- Share intelligence with stakeholders

### Types of Reports
- Strategic Reports
- Operational Reports
- Tactical Reports
- Executive Reports

---

## Module 7: Threat Intelligence Program Management

### Tools
- MISP
- OpenCTI
- ThreatConnect

### Frameworks
- MITRE ATT&CK
- NIST

### Purpose
- Manage threat intelligence programs
- Improve intelligence sharing
- Measure program maturity

---

# Top CTIA Tools to Learn

1. Maltego
2. Shodan
3. VirusTotal
4. MISP
5. Netcraft
6. SpiderFoot
7. WHOIS
8. DNSDumpster
9. MXToolbox
10. Any.Run
11. Hybrid Analysis
12. Wireshark
13. AlienVault OTX
14. Censys
15. MITRE ATT&CK

---

# Typical CTIA Investigation Workflow

```text
GHDB
  ↓
WHOIS
  ↓
DNSDumpster
  ↓
Netcraft
  ↓
Shodan
  ↓
VirusTotal
  ↓
Maltego
  ↓
MISP
```

## Workflow Explanation

1. **GHDB** – Discover exposed information using Google Dorks.
2. **WHOIS** – Identify domain ownership and registration details.
3. **DNSDumpster** – Enumerate DNS records and subdomains.
4. **Netcraft** – Analyze hosting infrastructure and technologies.
5. **Shodan** – Discover internet-facing assets and services.
6. **VirusTotal** – Check reputation of files, URLs, domains, and IPs.
7. **Maltego** – Correlate data and visualize relationships.
8. **MISP** – Store, enrich, and share threat intelligence.

This workflow helps a Threat Intelligence Analyst collect, analyze, enrich, and share intelligence during investigations.
