# Module 01: Introduction to Threat Intelligence

## 1. Understanding Intelligence

### What is Intelligence?
Intelligence is analyzed and processed information that supports decision-making. It is derived from data and information to provide actionable insights.

### Data
Raw facts without context.

**Examples:**
- IP Address: `192.168.1.10`
- Hash: `44d88612fea8a8f36de82e1278abb02`

### Information
Processed data that provides context.

**Examples:**
- The IP address belongs to a TOR exit node.
- The hash is associated with malware.

### Intelligence
Analyzed information that enables action and decision-making.

**Example:**
- The IP address has been used by ransomware groups targeting financial institutions.

**Flow:**  
`Data → Information → Intelligence → Decision`

---

## Types of Intelligence

### Strategic Intelligence
Provides high-level information for executives and management.

**Example:**
- Increase in ransomware attacks against healthcare organizations.

### Operational Intelligence
Focuses on threat actors, campaigns, and attack operations.

**Example:**
- An APT group is targeting government organizations.

### Tactical Intelligence
Provides information about attacker Tactics, Techniques, and Procedures (TTPs).

**Example:**
- Attackers are using PowerShell for lateral movement.

### Technical Intelligence
Provides Indicators of Compromise (IOCs).

**Examples:**
- IP Addresses
- Domains
- URLs
- File Hashes

---

## 2. Cyber Threat Intelligence (CTI) Concepts

### What is Cyber Threat Intelligence (CTI)?
Cyber Threat Intelligence (CTI) is the process of collecting, processing, analyzing, and sharing information about cyber threats, threat actors, vulnerabilities, and attack techniques.

### Gathering Information
Sources include:
- Security Logs
- Threat Intelligence Feeds
- Open Source Intelligence (OSINT)
- Dark Web Sources
- Malware Samples
- Incident Reports

### Processing Information
Activities include:
- Removing duplicate data
- Filtering irrelevant information
- Organizing data into a structured format

### Analyzing Information
Analysis helps answer:
- Who is behind the attack?
- What is the attacker's objective?
- Which vulnerability is being targeted?
- What could happen next?

### Sharing Information
Information may be shared with:
- SOC Teams
- Incident Response Teams
- Security Teams
- Management
- External Partners

---

## Cyber Threats

Examples:
- Malware
- Ransomware
- Phishing
- DDoS Attacks
- Insider Threats

## Threat Actors

Examples:
- Cybercriminals
- Nation-State Hackers
- Hacktivists
- Insider Threats
- Terrorist Organizations

**Notable Threat Actors:**
- Lazarus Group
- APT29
- FIN7

## Vulnerabilities

Weaknesses in software, systems, or networks that attackers can exploit.

**Example:**
- An unpatched software vulnerability that allows unauthorized access.

## Attack Techniques

Examples:
- Phishing
- Credential Theft
- SQL Injection
- Malware Delivery
- Privilege Escalation
- Lateral Movement

---

## Goals of Cyber Threat Intelligence (CTI)

### 1. Predict Cyber Attacks Before They Happen
Identify potential threats before attacks occur.

### 2. Understand Attacker Behavior
Understand:
- Attacker motives
- Techniques used
- Preferred targets
- Attack patterns

### 3. Improve Security Defenses
Examples:
- Updating firewall rules
- Improving SIEM detection rules
- Enhancing security policies

### 4. Support Incident Response and SOC Operations
Provides intelligence for:
- Detection
- Investigation
- Response

### 5. Reduce Organizational Risk

**Reactive Approach**
- Attack occurs
- Investigation starts

**Proactive Approach**
- Threat identified early
- Security controls updated
- Attack prevented

---

## Why CTI is Important

### 1. Identifying Emerging Threats
Discover new threats before they become widespread.

### 2. Tracking Threat Actors
Understand:
- Who the attackers are
- What their objectives are
- Which industries they target
- How they conduct attacks

### 3. Monitoring Indicators of Compromise (IOCs)

Common IOCs:
- Malicious IP Addresses
- Suspicious Domain Names
- File Hashes
- Email Addresses
- URLs

### 4. Understanding Tactics, Techniques, and Procedures (TTPs)

#### Tactics
- Initial Access
- Persistence
- Data Exfiltration

#### Techniques
- Phishing
- Exploiting Vulnerabilities
- Credential Theft

#### Procedures
Specific steps or tools used during an attack.

### 5. Supporting Threat Hunting Activities

Threat hunters use CTI to:
- Identify suspicious behavior
- Search for attacker techniques
- Detect missed threats

---

## Threat Intelligence Lifecycle

### Phase 1: Requirements
Define intelligence goals and requirements.

### Phase 2: Collection
Sources:
- OSINT
- Security Logs
- Threat Feeds
- Dark Web Sources
- Internal Security Tools

### Phase 3: Processing
Activities:
- Data Normalization
- Data Filtering
- Data Categorization
- Duplicate Removal

### Phase 4: Analysis
Questions:
- Who is attacking?
- Why are they attacking?
- How are they attacking?
- What is the impact?

### Phase 5: Dissemination
Recipients:
- SOC Analysts
- Incident Response Teams
- Security Managers
- Executives

### Phase 6: Feedback
Collect feedback and improve future intelligence operations.

---

## Threat Intelligence Frameworks

### MITRE ATT&CK Framework

Common Tactics:
- Initial Access
- Execution
- Persistence
- Privilege Escalation
- Defense Evasion
- Credential Access
- Discovery
- Lateral Movement
- Collection
- Exfiltration
- Command and Control

### Cyber Kill Chain

Stages:
1. Reconnaissance
2. Weaponization
3. Delivery
4. Exploitation
5. Installation
6. Command and Control (C2)
7. Actions on Objectives

### Diamond Model of Intrusion Analysis

Components:
- Adversary
- Capability
- Infrastructure
- Victim

---

## Threat Intelligence Platforms (TIPs)

### What is a TIP?
A Threat Intelligence Platform (TIP) collects, aggregates, analyzes, enriches, and manages threat intelligence data.

### Functions
- Threat Data Collection
- Data Correlation
- IOC Management
- Intelligence Sharing
- Automation
- Threat Enrichment

### Benefits
- Centralized Intelligence Management
- Faster Threat Detection
- Improved Collaboration
- Reduced Manual Effort
- Better Incident Response

### Common TIP Solutions
- MISP
- OpenCTI
- ThreatConnect
- Anomali ThreatStream

---

## Threat Intelligence in Cloud Environments

### Common Cloud Threats
- Misconfiguration
- Credential Theft
- Data Exposure
- Malware Attacks
- Insider Threats

### Benefits of Cloud Threat Intelligence
- Enhanced Visibility
- Improved Detection Capabilities
- Threat Hunting Support
- Risk Reduction
- Better Cloud Security Monitoring

---

## Future Trends in Threat Intelligence

- Artificial Intelligence and Machine Learning
- Threat Intelligence Automation
- Real-Time Threat Intelligence
- Cloud-Native Threat Intelligence
- Threat Hunting Integration
- Intelligence Sharing

---

## Key Terms

- Cyber Threat Intelligence (CTI)
- Indicators of Compromise (IOCs)
- Threat Actor
- Tactics, Techniques, and Procedures (TTPs)
- MITRE ATT&CK
- Cyber Kill Chain
- Diamond Model
- Threat Intelligence Platform (TIP)
- Threat Hunting
- Incident Response
