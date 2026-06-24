# CTIA Module 03: Requirements, Planning, Direction, and Review

> Comprehensive Study Notes for CTIA (Certified Threat Intelligence Analyst)

---

# Module Overview

A Cyber Threat Intelligence (CTI) Program cannot succeed without proper planning and management.

Before collecting intelligence, an organization must answer four critical questions:

| Phase        | Question                                    |
| ------------ | ------------------------------------------- |
| Requirements | What intelligence do we need?               |
| Planning     | How will we build the intelligence program? |
| Direction    | Who will guide and support the program?     |
| Review       | How do we know the program is successful?   |

---

# CTI Program Lifecycle

```text
Requirements
      ↓
Planning
      ↓
Direction
      ↓
Review
```

Memory Trick:

```text
Need It
   ↓
Build It
   ↓
Manage It
   ↓
Measure It
```

---

# Part 1: Requirements

## What are Requirements?

Requirements are the intelligence needs of an organization.

Before collecting intelligence, analysts must determine:

* What information is needed
* Why it is needed
* Who requires it
* How it will be used

### Example

A bank may ask:

* Who is targeting us?
* What malware is being used?
* Which vulnerabilities are being exploited?
* How are attacks being conducted?

These questions become Intelligence Requirements.

---

# LO#02: Requirements Analysis

## Definition

Requirements Analysis is the process of identifying intelligence needed to support business and security decisions.

---

## Current State vs Target State

### Current State

Current security posture of the organization.

#### Example

* No CTI Team
* Manual Analysis
* Slow Detection
* Limited Visibility

### Target State

Desired future security posture.

#### Example

* Dedicated CTI Team
* Automated Intelligence Collection
* Rapid Detection
* Threat Hunting Capability

---

# Identify Critical Elements

## Critical IT Assets

Systems essential for business operations.

### Examples

* Servers
* Databases
* Cloud Infrastructure
* Email Systems

---

## Valuable Internal Assets

Assets attackers want to steal.

### Examples

* Customer Records
* Financial Data
* Intellectual Property
* Employee Information

---

## Threat Actors

Individuals or groups performing malicious activities.

### Examples

* Cybercriminals
* Nation-State Actors
* Hacktivists
* Insider Threats

---

# Tactics, Techniques and Procedures (TTPs)

## Tactics

High-level attacker objectives.

### Examples

* Credential Access
* Persistence
* Exfiltration

---

## Techniques

Methods used to achieve objectives.

### Examples

* Phishing
* Password Spraying
* Exploitation

---

## Procedures

Specific implementation steps.

### Example

Sending fake Microsoft login pages to employees.

---

## TTP Example

| Category  | Example                   |
| --------- | ------------------------- |
| Tactic    | Credential Access         |
| Technique | Phishing                  |
| Procedure | Fake Microsoft Login Page |

---

# Existing Security Capabilities

Current security controls.

### Examples

* SIEM
* IDS
* IPS
* EDR
* Firewalls

---

# Staff Capabilities

Questions:

* Can analysts perform malware analysis?
* Can analysts conduct threat hunting?
* Can analysts investigate incidents?
* Can analysts analyze intelligence?

---

# Collaboration Teams

Teams involved in cybersecurity operations.

### Examples

* SOC Team
* Incident Response Team
* Vulnerability Management Team
* IT Operations Team

---

# Intelligence Requirements

Intelligence Requirements are questions that intelligence must answer.

---

## WHO?

Who is attacking us?

### Examples

* APT29
* LockBit
* FIN7

---

## WHY?

Why are they attacking?

### Motivations

* Financial Gain
* Espionage
* Political Influence
* Sabotage

---

## WHAT?

What malware or tools are being used?

### Examples

* Ransomware
* RATs
* Botnets

---

## WHEN?

When do attacks occur?

### Examples

* Holidays
* Major Company Events
* Product Launches

---

## HOW?

How are attacks performed?

### Examples

* Phishing
* Exploit Kits
* Supply Chain Attacks

---

## WHERE?

Where do attacks originate?

### Examples

* Dark Web
* Malicious Domains
* Compromised Infrastructure

---

# Intelligence Requirement Framework

| Question                             | Intelligence Type                    |
| ------------------------------------ | ------------------------------------ |
| Who are our adversaries?             | Threat Actor Intelligence            |
| Are we protected from botnets?       | Botnet Intelligence                  |
| Which vulnerabilities are exploited? | Malware & Vulnerability Intelligence |

---

# Defining Threat Intelligence Requirements

Benefits:

* Better Collection
* Reduced Cost
* Better Dissemination
* Improved Detection
* Better Decision Making

---

# Primary CTI Use Cases

## Prevention

Prevent attacks before they occur.

Example:

Block malicious IP addresses.

---

## Detection

Identify attacks quickly.

Example:

Detect ransomware activity.

---

## Forensics

Investigate incidents after compromise.

Example:

Determine attacker entry point.

---

## Threat Hunting

Search proactively for hidden threats.

Example:

Identify attacker activity missed by security tools.

---

# Intelligence Consumption Methods

## Automated Blocking

Automatically block malicious indicators.

### Example

Firewall blocks known malicious IP addresses.

---

## SIEM Integration

Threat intelligence enriches SIEM alerts.

### Example

Alert generated when a host communicates with a malicious domain.

---

## Threat Hunting

Use intelligence to discover hidden threats.

---

# Threat Intelligence Requirement Categories

## PIC Model

```text
P = Production Requirements
I = Intelligence Requirements
C = Collection Requirements
```

---

## Production Requirements

Specify intelligence products that must be created.

### Examples

* Weekly Reports
* Executive Briefings
* Threat Bulletins
* Situation Reports

Question:

**What must be produced?**

---

## Intelligence Requirements

Questions requiring intelligence analysis.

Question:

**What must be known?**

### Examples

* Which ransomware groups target healthcare?
* What malware targets financial institutions?

---

## Collection Requirements

Specify data required to satisfy intelligence requirements.

Question:

**What data must be collected?**

---

# Collection Sources

## External Sources

* Threat Actors
* Threat Feeds
* Security Forums
* Security Blogs
* Social Media
* GHDB (Google Hacking Database)

---

## Internal Sources

### Attack Surface

Assets exposed to attackers.

### Internal Telemetry

System-generated logs.

Examples:

* Firewall Logs
* SIEM Logs
* Endpoint Logs

---

# Business Requirements

Threat Intelligence must support business objectives.

Questions:

* How can CTI improve risk management?
* How can CTI support audits?
* How can CTI support compliance?
* How can CTI protect critical assets?

---

# Internal Stakeholders

## Business Executives

Need:

* Revenue Protection
* Asset Protection

## Management

Need:

* Confidential Information Protection

## End Users

Need:

* Account Protection
* Personal Data Protection

## CIO

Needs:

* Visibility into Technology Risks

## CISO / Security Manager / Analysts

Responsible for implementing intelligence requirements.

---

# Third-Party Requirements

## Contractors

Monitor outsourced risks.

## Suppliers

Ensure secure service delivery.

---

# Part 2: Planning

## Definition

Planning determines how the Threat Intelligence Program will be built.

---

# Three Core Components

## People

Who performs intelligence activities?

Examples:

* CTI Analysts
* Threat Hunters
* Incident Responders

---

## Process

How intelligence is:

* Collected
* Analyzed
* Shared

---

## Technology

Tools supporting CTI operations.

Examples:

* SIEM
* TIP
* Threat Feeds

---

# Collection Plan

Defines:

* What to collect
* Where to collect
* How often to collect

---

# Program Schedule

Defines:

* Timelines
* Milestones
* Deliverables

---

# Budget

Includes:

* Threat Feeds
* TIP Licenses
* Personnel Costs
* Training Costs

---

# Communication Plan

Defines how intelligence is distributed.

Examples:

* Daily Reports
* Weekly Briefings
* Monthly Reports

---

# Threat Intelligence Aggregation

Combines intelligence from multiple sources.

Benefits:

* Improved Visibility
* Better Context
* Enhanced Detection

---

# Threat Intelligence Platform (TIP)

Centralized platform used to manage intelligence.

Functions:

* Collection
* Correlation
* Enrichment
* Distribution

---

# Intelligence Supports

* Detection
* Prevention
* Threat Hunting
* Incident Response

---

# Metrics Tracking

Measures:

* Program Effectiveness
* Intelligence Quality
* Security Improvements

---

# Part 3: Direction

## Definition

Direction provides leadership and support for the CTI Program.

Without management support, CTI initiatives often fail.

---

# Establish Management Support

## Project Charter

Defines:

* Scope
* Objectives
* Roles
* Responsibilities

---

## Threat Intelligence Policy

Defines:

* Governance
* Rules
* Standards

---

## Business Case

Explains:

### Risks

What happens without CTI?

### Benefits

What value CTI provides.

### ROI

Return on Investment.

Demonstrates how CTI reduces losses.

---

## Strategic Alignment

CTI must support:

* Business Goals
* Risk Management
* Compliance Requirements

---

# Build a Threat Intelligence Team

## CTI Analyst

Analyzes intelligence.

## Threat Hunter

Searches for hidden threats.

## Malware Analyst

Analyzes malware.

## Incident Responder

Handles incidents.

## Intelligence Manager

Leads CTI operations.

---

# Part 4: Review

## Definition

Review determines whether the CTI Program is meeting objectives.

---

# Threat Intelligence Sharing

Intelligence becomes more valuable when shared.

## Sharing Partners

* Government Agencies
* ISACs
* Vendors
* Industry Peers
* Security Communities

---

# Sharing Requirements

* Trust
* Confidentiality
* Legal Compliance

---

# Protect During Sharing

* Indicators
* Reports
* Sources
* Collection Methods

---

# Program Review Areas

## Intelligence Effectiveness

Was intelligence useful?

## Threat Coverage

Are all major threats covered?

## Detection Improvements

Has detection improved?

## Stakeholder Satisfaction

Are stakeholders satisfied?

## Operational Effectiveness

Are intelligence processes efficient?

---

# Success Metrics

## Incident Reduction

Fewer successful attacks.

## Faster Detection

Threats identified sooner.

## Faster Response

Incidents contained more quickly.

## Improved Security Posture

Overall security improvement.

---

# CTIA Module 03 Exam Memory Map

```text
REQUIREMENTS
│
├── Current State
├── Target State
├── Intelligence Requirements
├── PIC Model
│   ├── Production
│   ├── Intelligence
│   └── Collection
└── Business Requirements

PLANNING
│
├── People
├── Process
├── Technology
├── Collection Plan
├── Budget
└── Communication Plan

DIRECTION
│
├── Management Support
├── Project Charter
├── Threat Intelligence Policy
├── Business Case
└── CTI Team

REVIEW
│
├── Intelligence Sharing
├── Program Review
├── Metrics
├── Incident Reduction
├── Faster Detection
└── Faster Response
```

---

# Quick Revision

## PIC Model

* Production = What to Produce
* Intelligence = What to Know
* Collection = What to Collect

## Planning

* People
* Process
* Technology

## CTI Team

* CTI Analyst
* Threat Hunter
* Malware Analyst
* Incident Responder
* Intelligence Manager

## Success Metrics

* Incident Reduction
* Faster Detection
* Faster Response
* Improved Security Posture

---

**Author:** CTIA Study Notes
**Module:** Requirements, Planning, Direction and Review
**Purpose:** Exam Preparation + Training + Teaching Material
