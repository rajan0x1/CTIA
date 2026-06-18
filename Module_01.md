# Module 01: Introduction to Threat Intelligence


Module 01: Introduction to Threat Intelligence

1. Understanding Intelligence

What is Intelligence?

Intelligence is analyzed and processed information that supports decision-making. It is derived from data and information to provide actionable insights.

Data

Raw facts without context.

Example:

IP Address: 192.168.1.10

Hash: 44d88612fea8a8f36de82e1278abb02

Information

Processed data that provides context.

Example:

The IP address belongs to a TOR exit node.

The hash is associated with malware.

Intelligence

Analyzed information that enables action and decision-making.

Example:

The IP address has been used by ransomware groups targeting financial institutions.

Data → Information → Intelligence

Data → Information → Intelligence → Decision

Types of Intelligence

Strategic Intelligence

Provides high-level information for executives and management.

Example:

Increase in ransomware attacks against healthcare organizations.

Operational Intelligence

Focuses on threat actors, campaigns, and attack operations.

Example:

An APT group is targeting government organizations.

Tactical Intelligence

Provides information about attacker tactics, techniques, and procedures (TTPs).

Example:

Attackers are using PowerShell for lateral movement.

Technical Intelligence

Provides indicators of compromise (IOCs).

Examples:

IP Addresses

Domains

URLs

File Hashes

2. Cyber Threat Intelligence Concepts

What is Cyber Threat Intelligence (CTI)?

Cyber Threat Intelligence (CTI) is the process of collecting, processing, analyzing, and sharing information about cyber threats, threat actors, vulnerabilities, and attack techniques.

Gathering Information

Gathering means collecting data related to cyber threats from different sources.

Sources include:

Security logs

Threat intelligence feeds

Open Source Intelligence (OSINT)

Dark web sources

Malware samples

Incident reports

Example:
An organization collects information about a new ransomware campaign targeting businesses.

Processing Information

Processing means organizing and cleaning the collected data so it becomes useful.

Activities include:

Removing duplicate data

Filtering irrelevant information

Organizing data into a structured format

Example:
The same malicious IP address is found in multiple sources and merged into a single record.

Analyzing Information

Analyzing means studying the processed data to understand the threat.

Analysis helps answer:

Who is behind the attack?

What is the attacker's objective?

Which vulnerability is being targeted?

What could happen next?

Example:
Analysis reveals that a ransomware group is targeting healthcare organizations.

Sharing Information

Sharing means distributing intelligence to teams that can use it for security operations.

Information may be shared with:

SOC Teams

Incident Response Teams

Security Teams

Management

External Partners

Example:
A list of malicious IP addresses is shared with the SOC team for monitoring and blocking.

Cyber Threats

Cyber threats are activities that can damage systems, networks, or data.

Examples:

Malware

Ransomware

Phishing

DDoS Attacks

Insider Threats

Threat Actors

Threat actors are individuals or groups responsible for cyber attacks.

Examples:

Cybercriminals

Nation-State Hackers

Hacktivists

Insider Threats

Terrorist Organizations

Example:
Lazarus Group, APT29, FIN7.

Vulnerabilities

Vulnerabilities are weaknesses in software, systems, or networks that attackers can exploit.

Example:
An unpatched software vulnerability that allows unauthorized access.

Attack Techniques

Attack techniques are methods used by attackers to compromise systems.

Examples:

Phishing

Credential Theft

SQL Injection

Malware Delivery

Privilege Escalation

Lateral Movement

Example:
An attacker sends a phishing email to steal user credentials.

Goals of Cyber Threat Intelligence (CTI)

1. Predict Cyber Attacks Before They Happen

CTI helps organizations identify potential threats before an attack occurs.

Example:
Threat intelligence reports indicate that a ransomware group is targeting banks.

2. Understand Attacker Behavior

CTI helps understand:

Attacker motives

Techniques used

Preferred targets

Attack patterns

Example:
An Advanced Persistent Threat (APT) group frequently uses spear-phishing attacks.

3. Improve Security Defenses

CTI helps organizations strengthen security controls.

Examples:

Updating firewall rules

Improving SIEM detection rules

Enhancing security policies

4. Support Incident Response and SOC Operations

CTI provides valuable information for detecting, investigating, and responding to security incidents.

Example:
A SOC analyst checks an IP address and discovers it is associated with known malicious activity.

5. Reduce Organizational Risk

CTI helps organizations move from a reactive approach to a proactive approach.

Reactive Approach:

Attack occurs

Investigation starts

Proactive Approach:

Threat identified early

Security controls updated

Attack prevented

Why CTIA is Important

Traditional cybersecurity is often reactive, which means organizations respond after an attack has already happened.

Cyber Threat Intelligence (CTI) helps organizations become proactive by identifying threats before they cause damage.

1. Identifying Emerging Threats

CTI helps organizations discover new and developing cyber threats before they become widespread.

Example:
Security researchers identify a new ransomware campaign targeting financial institutions. Organizations can prepare and strengthen their defenses before being attacked.

2. Tracking Threat Actors

CTI helps monitor the activities of cybercriminals, hacker groups, and nation-state attackers.

Organizations can understand:

Who the attackers are

What their objectives are

Which industries they target

How they conduct attacks

Example:
A threat intelligence report shows that a specific APT group is targeting government organizations.

3. Monitoring Indicators of Compromise (IOCs)

Indicators of Compromise (IOCs) are pieces of evidence that indicate malicious activity.

Common IOCs include:

Malicious IP addresses

Suspicious domain names

File hashes

Email addresses

URLs

Example:
If a known malicious IP address appears in network logs, the SOC team can investigate immediately.

4. Understanding Attacker Tactics, Techniques, and Procedures (TTPs)

TTPs describe how attackers operate.

Tactics

The attacker's goal or objective.

Example:

Initial Access

Persistence

Data Exfiltration

Techniques

The methods used to achieve the objective.

Example:

Phishing

Exploiting vulnerabilities

Credential theft

Procedures

The specific steps or tools used during an attack.

Example:
Using a phishing email with a malicious attachment to gain access to a system.

Understanding TTPs helps organizations predict attacker behavior and improve detection capabilities.

5. Supporting Threat Hunting Activities

Threat hunting is the proactive search for hidden threats within a network.

CTI provides intelligence that helps threat hunters:

Identify suspicious behavior

Search for known attacker techniques

Detect threats that security tools may have missed

Example:
Threat hunters use intelligence about a ransomware group's behavior to search for similar activity inside the organization's environment.

Threat Intelligence Lifecycle

The Threat Intelligence Lifecycle is a continuous process used to collect, analyze, and distribute intelligence.

Phase 1: Requirements

Define intelligence goals and requirements.

Example Questions:

Who is targeting our organization?

What threats are most relevant to our industry?

Phase 2: Collection

Gather threat-related data from various sources.

Sources Include:

Open Source Intelligence (OSINT)

Security Logs

Threat Feeds

Dark Web Sources

Internal Security Tools

Phase 3: Processing

Convert raw data into a usable format.

Activities include:

Data normalization

Data filtering

Data categorization

Removing duplicate information

Phase 4: Analysis

Analyze processed information to identify patterns and generate intelligence.

Analysts answer:

Who is attacking?

Why are they attacking?

How are they attacking?

What is the impact?

Phase 5: Dissemination

Deliver intelligence to stakeholders.

Recipients may include:

SOC Analysts

Incident Response Teams

Security Managers

Executives

Phase 6: Feedback

Collect feedback and improve future intelligence operations.

The lifecycle then repeats continuously.

Threat Intelligence Frameworks

Threat Intelligence frameworks help analysts understand attacker behavior and improve investigations.

MITRE ATT&CK Framework

The MITRE ATT&CK Framework is a knowledge base of adversary tactics and techniques observed in real-world attacks.

Common ATT&CK Tactics

Initial Access

Execution

Persistence

Privilege Escalation

Defense Evasion

Credential Access

Discovery

Lateral Movement

Collection

Exfiltration

Command and Control

Cyber Kill Chain

Developed to describe the stages of a cyber attack.

Stages of Cyber Kill Chain

Reconnaissance

Weaponization

Delivery

Exploitation

Installation

Command and Control (C2)

Actions on Objectives

Diamond Model of Intrusion Analysis

The Diamond Model consists of four key elements:

Adversary

The threat actor conducting the attack.

Capability

Tools, malware, and techniques used by the attacker.

Infrastructure

Systems and resources used to conduct the attack.

Victim

The target of the attack.

Threat Intelligence Platforms (TIPs)

What is a Threat Intelligence Platform?

A Threat Intelligence Platform (TIP) is a solution that collects, aggregates, analyzes, enriches, and manages threat intelligence data.

Functions of a TIP

Threat Data Collection

Data Correlation

IOC Management

Intelligence Sharing

Automation

Threat Enrichment

Benefits of TIPs

Centralized Intelligence Management

Faster Threat Detection

Improved Collaboration

Reduced Manual Effort

Better Incident Response

Common TIP Solutions

MISP

OpenCTI

ThreatConnect

Anomali ThreatStream

Threat Intelligence in Cloud Environments

Cloud computing introduces new security challenges that require threat intelligence support.

Common Cloud Threats

Misconfiguration

Incorrect security settings exposing resources.

Credential Theft

Compromised cloud accounts.

Data Exposure

Unauthorized access to sensitive data.

Malware Attacks

Malware targeting cloud-hosted workloads.

Insider Threats

Malicious or negligent user activity.

Benefits of Cloud Threat Intelligence

Enhanced visibility

Improved detection capabilities

Threat hunting support

Risk reduction

Better cloud security monitoring

Future Trends in Threat Intelligence

Artificial Intelligence and Machine Learning

AI-driven threat detection and intelligence analysis.

Threat Intelligence Automation

Automated collection, enrichment, and response.

Real-Time Threat Intelligence

Immediate threat detection and notification.

Cloud-Native Threat Intelligence

Intelligence designed specifically for cloud environments.

Threat Hunting Integration

Combining CTI with proactive threat hunting activities.

Intelligence Sharing

Increased collaboration between organizations and security communities.

Key Terms

Cyber Threat Intelligence (CTI)

Indicators of Compromise (IOCs)

Threat Actor

Tactics, Techniques, and Procedures (TTPs)

MITRE ATT&CK

Cyber Kill Chain

Diamond Model

Threat Intelligence Platform (TIP)

Threat Hunting

Incident Response