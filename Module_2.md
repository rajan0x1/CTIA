# Module 2: Cyber Threats and Attack Frameworks
> Professional GitHub-ready study notes with hierarchical headings, bullets, key points, examples, and teaching-friendly structure.


#### Module 2: Cyber Threats and Attack Frameworks

---

## #01: Understand Cyber Threats

### 1. What is a Cyber Threat?
- A cyber threat is any danger or malicious activity that can harm a computer, network, application, or digital system.

**The goal is usually to break one of the three security principles:**

#### CIA Triad

#### Confidentiality
- Information should only be seen by authorized people.
- Example: A hacker steals customer passwords.

#### Integrity
- Information should remain accurate and unchanged.
- Example: A hacker changes bank account balances.

#### Availability
- Systems and data should be available when needed.
- Example: A DDoS attack makes a website unavailable.

#### Simple Definition
- Cyber Threat = Anything that can steal, change, or block information.

#### Why Do Cyber Attacks Happen?

**Attackers may want to:**

#### Steal data

#### Steal money

#### Damage reputation

#### Stop business operations

#### Gain unauthorized access

#### Demand ransom

#### Spy on organizations or governments

### 2. Cyber Security Threat Categories

**Cyber threats are divided into three main groups:**

#### A. Network Threats
- These attacks target the network and communication systems.

#### Think:
👉 "Data moving between devices"

#### Common Network Threats

#### Malware Transmission
- Malware spreads through a network.
- Example:
One infected computer infects others.

#### DoS (Denial of Service)
- An attacker sends huge traffic to a server.
- Result:
The server becomes overloaded and stops responding.
- Example:
100,000 fake requests sent to a website.

#### DDoS (Distributed DoS)
- Same as DoS, but traffic comes from many computers.
- Example:
A botnet attacks a website from thousands of infected devices.

#### Packet Sniffing
- Capturing network traffic.
- Example:
Stealing usernames and passwords sent over a network.

#### Man-in-the-Middle (MitM)
- The attacker secretly sits between two communicating parties.
- Example:
You think you're talking to a bank, but a hacker intercepts everything.

#### Network Scanning

**Searching for:**

#### Open ports

#### Running services

#### Vulnerabilities
- Think:
👉 Reconnaissance before an attack.

#### Enumeration
- Collecting detailed information about a target.
- Example:
Finding usernames, shares, and services.

#### Eavesdropping
- Secretly listening to communications.
- Example:
Listening to unencrypted Wi-Fi traffic.

#### DNS Spoofing
- DNS Poisoning is a cyber attack in which an attacker manipulates DNS records to redirect users from a legitimate website to a fake or malicious website.Example:
Typing "bank.com" but opening a hacker's fake site.

#### Phishing
- Tricking users into giving information.
- Example:
Fake email asking for login credentials.

#### B. Host Threats
- These attacks target individual devices.
- Think:
👉 Computer, laptop, server, endpoint.

#### Malware Infection
- Malicious software infects a system.

**Examples:**

#### Virus

#### Worm

#### Trojan

#### Ransomware
- Encrypts files and demands money.

#### Example:
"Pay $5000 to recover your files."

#### Unauthorized Access
- Someone accesses a system without permission.

#### Brute Force Attack
- Repeatedly trying passwords until one works.
- Example:
Trying thousands of password combinations.

#### Insider Threat
- Threat from a trusted person.

**Examples:**

#### Employee

#### Contractor

#### Administrator

#### Unauthorized Configuration Changes
- Changing security settings without permission.

#### Physical Theft/Tampering
- Stealing or physically manipulating a device.

#### Rootkits
- Rootkit is a type of malicious software designed to hide its presence and provide attackers with privileged (root/administrator) access to a system.
- It operates stealthily, making it difficult to detect, and can be used to maintain persistent access, steal data, or control a compromised device without the user's knowledge.

#### Backdoors
- Backdoor is a hidden method of bypassing normal authentication or security controls to gain unauthorized access to a system, application, or network.
- Attackers use backdoors to maintain persistent access to compromised systems, allowing them to remotely control the system, steal data, or execute malicious activities without being detected.

**Attackers create or use backdoors in several ways:**
- Installing Malware: After compromising a system through phishing, exploits, or malware, attackers install a backdoor program that allows them to reconnect later.
- Exploiting Vulnerabilities: Attackers abuse unpatched software flaws to gain access and then create a hidden access mechanism.
- Trojanized Software: They hide backdoors inside seemingly legitimate software, cracked applications, or malicious updates.
- Creating Hidden Accounts: Attackers may create secret administrator accounts or modify authentication mechanisms to maintain access.
- Example:
An attacker sends a phishing email containing malware. Once executed, the malware installs a backdoor that connects to the attacker's Command and Control (C2) server, allowing remote access whenever needed.

#### Privilege Escalation
- Gaining higher permissions.
- Example:
A normal user becomes administrator.

#### Fileless Attacks
- Fileless Attack is a type of cyberattack that operates primarily in memory without writing malicious files to the disk, making it difficult for traditional antivirus solutions to detect.
- Attackers typically use legitimate tools such as PowerShell, Windows Management Instrumentation (WMI), or malicious macros to execute commands directly in memory and maintain persistence on the compromised system.

**How a Fileless Attack Happens:**
- The attacker sends a phishing email containing a malicious link or document.
- When the user clicks the link or enables macros, a script (e.g., PowerShell) is executed.
- Instead of downloading a malware file to disk, the script runs directly in RAM (memory).
- The attacker then uses legitimate system tools like PowerShell, WMI, or Windows Registry to execute commands, steal data, or maintain access.
- Example:
A user opens a malicious Word document and enables macros. The macro launches a PowerShell command that downloads and executes malicious code directly in memory, leaving little or no file evidence on the hard drive.

#### C. Application Threats
- These attacks target software and web applications.
- Think:
👉 Websites, APIs, web apps.

#### SQL Injection (SQLi)
- Attacker inserts malicious SQL commands.

**Example:**

#### ' OR 1=1 --
- Can access or modify databases.

#### Cross-Site Scripting (XSS)
- Injecting malicious JavaScript into websites.
- Result:
Cookies and sessions can be stolen.

#### Cross-Site Request Forgery (CSRF)
- Forces a logged-in user to perform actions.
- Example:
Changing account settings without user knowledge.

#### Code Injection
- Running unauthorized code in an application.

#### API Vulnerabilities
- Weaknesses in APIs that attackers exploit.

#### Zero-Day Vulnerabilities
- Unknown vulnerabilities.
- No patch exists yet.
- Very dangerous.

#### Supply Chain Attacks
- Compromising trusted software or vendors.
- Example:
Attacker infects software updates.

#### Broken Authentication
- Weak login systems.

**Examples:**

#### Weak passwords

#### Poor session management

#### Security Misconfiguration
- Incorrect security settings.
- Example:
Public cloud storage exposed to everyone.

### 3. Cyber Threats in Specialized Technologies

#### A. Industrial Control Systems (ICS)

**Used in:**

#### Factories

#### Power plants

#### Manufacturing

#### Threats

#### Malware

#### Ransomware

#### Phishing

#### DoS

#### Weak authentication

#### Unauthorized access

#### B. Internet of Things (IoT)
- Smart connected devices.

**Examples:**

#### Smart cameras

#### Smart TVs

#### Smart thermostats

#### Threats

#### Weak passwords

#### Firmware vulnerabilities

#### Botnets

#### Malware

#### Data breaches

#### Example
- Thousands of smart cameras become part of a botnet and launch a DDoS attack.

#### C. Mobile Devices
- Smartphones and tablets.

#### Threats

#### Mobile malware

#### Data leakage

#### Phishing

#### Unauthorized access

#### Malicious apps

#### D. SCADA Systems
- SCADA Systems (Supervisory Control and Data Acquisition) are industrial control systems used to monitor and control critical infrastructure in real time.
- They collect data from sensors and devices (like pipelines, power grids, factories) and allow operators to control processes remotely through a central system.

#### Threats

#### Remote access vulnerabilities

#### Insider threats

#### Supply chain attacks

**Here’s a real-world style SCADA scenario:**

**Power Grid Monitoring System (SCADA Example):**
- In a city’s electricity distribution network, SCADA systems are installed at substations to monitor voltage, current, and load in real time.
- If one transformer starts overheating or a line gets overloaded, SCADA immediately sends an alert to the control room and can automatically switch the load to another substation to prevent blackout.
- Operators sitting in a control center can also remotely open/close circuit breakers, restore power after a fault, and balance electricity demand across the grid without physically going to the site.

#### E. RTOS (Real-Time Operating Systems)

**Used in:**

#### Medical devices

#### Embedded systems

#### Aircraft systems

#### Threats

#### Buffer overflow

#### Unauthorized access

#### DoS attacks

#### F. CAN Bus
- Used inside vehicles.
- Allows car components to communicate.

#### Threats

#### Message spoofing

#### Eavesdropping

#### Unauthorized access

### 4. Threat Actors (Attackers)
- A threat actor is anyone who performs cyber attacks.

#### Black Hats
- Bad hackers.

**Goals:**

#### Steal money

#### Steal data

#### Cause damage

#### White Hats
- Ethical hackers.

**Goals:**

#### Find vulnerabilities

#### Improve security

#### Gray Hats
- Between legal and illegal.
- May find vulnerabilities without permission.

#### Script Kiddies
- Unskilled attackers.
- Use ready-made hacking tools.

**Motives:**

#### Fun

#### Fame

#### Curiosity

#### Suicide Hackers
- Attack regardless of consequences.
- Goal:
Maximum damage.

#### Cyber Terrorists
- Politically or religiously motivated.
- Goal:
Create fear and chaos.
- Target:
Critical infrastructure.

### 5. ICO Triad
- Used by Cyber Threat Intelligence (CTI) analysts.

#### Intent

#### Why does the attacker want to attack?

**Examples:**

#### Money

#### Espionage

#### Sabotage

#### Capability

#### Can the attacker actually do it?

**Includes:**

#### Skills

#### Resources

#### Tools

#### Infrastructure

#### Opportunity

#### Is there a weakness available?

**Examples:**

#### Weak passwords

#### Vulnerabilities

#### Misconfigurations

#### Formula

#### Threat = Intent + Capability + Opportunity

#### Example
- A hacker wants money (Intent),
has ransomware tools (Capability),
and finds an unpatched system (Opportunity).
- ➡ Threat exists.

### 6. Motives, Goals, and Objectives

#### Formula

#### Attack = Motive + Method + Vulnerability

#### Common Motives

#### Financial Gain

#### Banking fraud

#### Ransomware

#### Crypto theft

#### Information Theft

#### Personal data

#### Trade secrets

#### Intellectual property

#### Business Disruption

#### Service outages

#### Production shutdowns

#### Reputation Damage

#### Website defacement

#### Public data leaks

#### Revenge

#### Former employees

#### Personal grudges

#### Political or Religious Reasons

#### Hacktivism

#### Cyber terrorism

#### Military Objectives

#### Cyber warfare

#### Espionage

#### Creating Fear and Chaos

#### Attacking critical infrastructure

#### Ransom Demands

#### Encrypt files

#### Demand payment

### 7. Hacking Forums
- Hacking Forums are online platforms where people discuss hacking techniques, cybersecurity tools, vulnerabilities, and sometimes illegal cyber activities.
- They can be used for both legitimate purposes (like learning cybersecurity, sharing research, discussing exploits for defense) and illegitimate purposes (like buying/selling stolen data, malware, or discussing attacks).

**Online communities where people discuss:**

#### Hacking techniques

#### Vulnerabilities

#### Security tools

#### Malware

#### Defenses

#### Why CTI Analysts Monitor Them

**To learn:**

#### New attack methods

#### New malware

#### Emerging threats
- These are online cybersecurity and hacking-related forums/websites where people discuss security, hacking techniques, tools, and vulnerabilities.

**Here’s a simple breakdown:**
- BHF.EE – A hacking/security discussion forum (less known, varies in activity over time).
- AntiOnline – One of the oldest security forums; focuses on cybersecurity discussions and hacking topics.
- Wilders Security Forums – Legit cybersecurity forum focused on antivirus, malware analysis, and system security.
- Hack The Box Forum – Official community forum of Hack The Box where users discuss penetration testing labs and challenges.
- Hackaday – A hardware and tech hacking blog/community focused on electronics, DIY security, and engineering projects.
- Hack Forums – A well-known forum often associated with both cybersecurity learning and also illegal hacking discussions.

### 8. Impact of Geopolitics and Economic Factors on Cyber Threats

#### Easy Idea
- Cyberattacks do not only affect computers.

**They can affect:**

#### Businesses

#### Economies

#### Governments

#### Entire countries

#### A. Economic Impact

### 1. Financial Loss
- Direct money loss.

**Examples:**

#### Ransom payments

#### Banking fraud

#### Data theft

**Impact:**

#### Revenue loss

#### Legal fines

#### Compensation costs

### 2. Reputational Damage
- Loss of trust.
- Example:
A company leaks customer data.

**Impact:**

#### Customers leave

#### Investors lose confidence

#### Negative publicity

### 3. Operational Disruption
- Business operations stop.

**Examples:**

#### Ransomware

#### DDoS attacks

#### Supply chain attacks

**Impact:**

#### Downtime

#### Lower productivity

#### Service interruptions

### 4. Increased Security Costs
- After an attack, organizations spend more on security.

**Examples:**

#### Incident response

#### Monitoring tools

#### Employee training

#### Infrastructure upgrades

#### B. Geopolitical Impact

### 1. State-Sponsored Attacks
- Government-backed cyber attacks.

**Goals:**
- Espionage : secretly collecting sensitive or classified information from a person, organization, or government without permission.
- It is commonly done for political, military, or corporate advantage, and in cybersecurity it often involves hacking, malware, or spying tools to steal data like secrets, plans, or credentials.

**How espionage happens (especially cyber espionage):**
- Phishing & social engineering – attackers trick people into giving passwords or opening malicious files.
- Malware installation – spyware or trojans are installed to secretly monitor systems and steal data.
- Exploiting vulnerabilities – attackers use unpatched software bugs to gain unauthorized access.
- Keyloggers & surveillance tools – they record keystrokes, screenshots, and system activity silently.
- Network infiltration (APT attacks) – advanced groups stay hidden in a network for long time and slowly collect sensitive data.
- Insider threat – employees or trusted users leak information intentionally or unknowingly.
- Example:
A government employee clicks a phishing email attachment. It installs spyware that silently sends classified documents to an attacker’s server over weeks or months without being detected.

#### Intelligence gathering

#### Infrastructure disruption

**Targets:**

#### Governments

#### Military systems

#### Critical infrastructure

### 2. Information Warfare
- Using the internet to influence people.

**Examples:**

#### Fake news

#### Social media manipulation

#### Propaganda

**Impact:**

#### Public confusion

#### Political instability

#### Election interference

### 3. Attacks on Public Services
- Critical services are attacked.

**Targets:**

#### Power grids

#### Hospitals

#### Transportation

#### Water systems

**Impact:**

#### Public safety risks

#### Economic damage

#### National security concerns

### 4. International Treaties and Regulations
- Countries cooperate to reduce cyber threats.

**Goals:**

#### Share threat intelligence

#### Improve cybersecurity

#### Prevent cyber warfare escalation

**Benefits:**

#### Better security

#### Faster incident response

#### Stronger international cooperation

---

## #02: Explain Advanced Persistent Threats (APTs)

### 1. What is an Advanced Persistent Threat (APT)?

#### Definition

**An Advanced Persistent Threat (APT) is a sophisticated cyberattack in which attackers:**

#### ✅ Gain unauthorized access to a network

#### ✅ Stay hidden for a long time

#### ✅ Continuously monitor and steal sensitive information

#### ✅ Avoid detection by security teams

#### Key Idea
- Unlike normal hackers who attack and leave quickly, APT attackers remain inside the network for weeks, months, or even years.

#### Easy Example

**Imagine a thief who:**

#### Breaks into a house secretly

#### Lives inside the attic for months

#### Watches everything

#### Steals valuable items little by little

#### Leaves without anyone noticing
- This is exactly how an APT attack works.

#### Why Are APT Attacks Dangerous?
- The goal is usually information theft, not destruction.
- APT attackers want long-term access to valuable information.

#### Information Stolen During APT Attacks

### 1. Classified Documents
- Government or military secrets.

**Example:**

#### Secret defense plans

### 2. User Credentials
- Login information.

**Examples:**

#### Usernames

#### Passwords

#### Authentication tokens

### 3. Employee or Customer Information
- Personal data.

**Examples:**

#### Names

#### Addresses

#### Phone numbers

#### Social Security Numbers

### 4. Network Information
- Details about the organization's infrastructure.

**Examples:**

#### IP addresses

#### Network diagrams

#### Security configurations

### 5. Transaction Information
- Financial transaction records.

**Examples:**

#### Banking transactions

#### Payment records

### 6. Credit Card Information
- Payment card details stolen for fraud.

### 7. Business Strategy Information
- Confidential company plans.

**Examples:**

#### Future products

#### Market expansion plans

#### Trade secrets

### 8. Control System Access Information
- Access details for industrial systems.

**Examples:**

#### Power plants

#### Water systems

#### Manufacturing facilities

### 2. Characteristics of APTs
- APTs have special features that make them different from ordinary cyberattacks.

#### A. Objectives

#### What does the attacker want?

**Usually:**

#### Obtain sensitive information

#### Conduct espionage

#### Achieve political goals

#### Gain military advantage

#### Steal intellectual property

#### Example
- A nation-state secretly steals defense research from another country.

#### B. Timeliness

#### Meaning

**The total time spent:**

#### Studying the target

#### Finding vulnerabilities

#### Gaining access

#### Maintaining access
- APT attacks take a long time.

#### Example

**An attacker spends:**

#### 2 months gathering information

#### 6 months inside the network

#### C. Resources

#### Meaning
- Amount of tools, money, knowledge, and infrastructure used.

**APT groups often have:**

#### Skilled hackers

#### Custom malware

#### Large budgets

#### Advanced technology

#### Example
- Government-sponsored cyber groups.

#### D. Risk Tolerance

#### Meaning
- How long attackers remain undetected.
- APT attackers carefully avoid detection.

#### Goal
- Stay hidden for months or years.

#### E. Skills and Methods

#### Meaning
- The techniques and tools used.

**Examples:**

#### Zero-day exploits

#### Custom malware

#### Social engineering

#### Spear phishing

#### Credential theft

#### F. Actions
- APT attacks consist of many coordinated actions.

**Examples:**

#### Reconnaissance

#### Initial compromise

#### Credential theft

#### Data collection

#### Data exfiltration

#### G. Attack Origination Points

#### Meaning
- APT attackers often try many entry points.

**Examples:**

#### Email attachments

#### Web applications

#### Remote access systems

#### Third-party vendors

#### Key Point
- They make multiple attempts until one succeeds.

#### Simple Memory Trick

#### APT Characteristics = OTRSSAA

#### O = Objectives

#### T = Timeliness

#### R = Resources

#### R = Risk Tolerance

#### S = Skills

#### A = Actions

#### A = Attack Origination Points

### 3. Advanced Persistent Threat (APT) Lifecycle
- APT attacks happen in several stages.
- Think of it as a step-by-step process.

#### Stage 1: Preparation

#### What Happens?
- The attacker gathers information.

**Also called:**

#### Reconnaissance

#### Activities

#### Research company

#### Find employees

#### Identify vulnerabilities

#### Collect email addresses

#### Example
- An attacker studies a company's LinkedIn profiles.

#### Stage 2: Initial Compromise

#### (Not always shown separately in diagrams but occurs after preparation)

#### What Happens?
- The attacker enters the network.

#### Methods

#### Spear phishing

#### Malware

#### Exploiting vulnerabilities

#### Example
- Employee opens a malicious email attachment.

#### Stage 3: Expansion

#### Goal
- Expand access inside the network.

#### Activities

#### Move laterally

#### Gain administrator rights

#### Steal credentials

#### Example
- A compromised user account becomes a domain administrator account.

#### Keywords

#### Credential theft

#### Privilege escalation

#### Lateral movement

#### Stage 4: Persistence

#### Goal
- Maintain long-term access.

#### Activities

#### Install backdoors

#### Create hidden accounts

#### Modify startup processes

#### Example
- A hidden administrator account is created.

#### Why?
- So attackers can return even if passwords change.

#### Stage 5: Search and Exfiltration

#### Goal
- Find and steal valuable information.

#### Activities

#### Search files

#### Collect data

#### Compress information

#### Transfer data outside the network

#### Exfiltration Means
- Secretly moving stolen data out of the victim's network.

#### Example
- Stealing customer databases and uploading them to attacker-controlled servers.

#### Stage 6: Cleanup

#### Goal
- Hide evidence.

#### Activities

#### Delete logs

#### Remove malware traces

#### Erase evidence

#### Result
- Security teams may never know the attack occurred.

#### Complete APT Lifecycle Flow

### 1. Preparation
        ↓
2. Initial Compromise
        ↓
3. Expansion
        ↓
4. Persistence
        ↓
5. Search & Exfiltration
        ↓
6. Cleanup

#### Real-World Example of an APT

#### Company Scenario
- Hacker researches employees.
- Sends a spear-phishing email.
- Employee clicks attachment.
- Malware is installed.
- Attacker steals credentials.
- Gains administrator access.
- Creates hidden backdoor.
- Stays inside network for months.
- Collects trade secrets.
- Exfiltrates data.
- Deletes logs and remains undetected.
- This is a classic APT attack.

---

## #03: Explain Cyber Kill Chain

### 1. What is the Cyber Kill Chain?

#### Definition
- The Cyber Kill Chain is a security model used to understand how cyber attackers perform an attack from start to finish.

**It helps security professionals:**

#### ✅ Understand attacker behavior

#### ✅ Identify attacks early

#### ✅ Stop attacks before damage occurs

#### ✅ Understand attacker TTPs (Tactics, Techniques, and Procedures)

#### Simple Idea
- Think of a cyberattack like a robbery.
- A thief doesn't suddenly steal something.

**The thief:**

#### Watches the target

#### Plans the robbery

#### Gets tools

#### Enters the building

#### Steals valuables

#### Escapes
- Similarly, cyber attackers follow a sequence of steps called the Cyber Kill Chain.

#### Cyber Kill Chain Phases

**There are 7 phases:**

### 1. Reconnaissance
        ↓
2. Weaponization
        ↓
3. Delivery
        ↓
4. Exploitation
        ↓
5. Installation
        ↓
6. Command & Control (C2)
        ↓
7. Actions on Objectives

#### Phase 1: Reconnaissance

#### Meaning
- The attacker gathers information about the target.

**Also called:**

#### Information Gathering

#### Activities

#### Collect employee details

#### Identify vulnerabilities

#### Find email addresses

#### Learn company structure

#### Identify technologies used

#### Example

**An attacker checks:**

#### LinkedIn

#### Facebook

#### Company website
- to gather information about employees.

#### Goal
- Find weak points to attack.

#### Phase 2: Weaponization

#### Meaning
- The attacker creates a malicious weapon.

**The weapon usually combines:**

#### Malware

#### Exploit

#### Backdoor

#### Example

**The attacker creates:**

#### A malicious PDF

#### A malicious Word document

#### An infected EXE file
- containing malware.

#### Goal
- Prepare the attack package.

#### Phase 3: Delivery

#### Meaning
- The attacker sends the malicious payload to the victim.

#### Delivery Methods

#### Phishing emails

#### USB drives

#### Websites

#### Social media

#### Messaging apps

#### Example
- The attacker emails a malicious attachment.

#### Goal
- Get the payload into the target environment.

#### Phase 4: Exploitation

#### Meaning
- The vulnerability is triggered.
- The malicious code executes.

#### Example
- An employee opens a malicious attachment.
- The malware exploits an unpatched vulnerability.

#### Activities

#### Execute malware

#### Exploit vulnerabilities

#### Escalate privileges

#### Goal
- Gain access to the system.

#### Phase 5: Installation

#### Meaning
- The attacker installs malware on the target system.

#### Example

**Malware installs:**

#### Trojan

#### Backdoor

#### Spyware

#### Goal
- Maintain long-term access.

#### Phase 6: Command and Control (C2)

#### Meaning
- The infected computer communicates with the attacker's server.

#### Example
- The malware contacts a hidden server on the internet.

**Now the attacker can:**

#### Send commands

#### Receive stolen data

#### Control the victim system

#### Goal
- Establish remote control.

#### Phase 7: Actions on Objectives

#### Meaning
- The attacker performs the final mission.

#### Possible Objectives

#### Steal data

#### Encrypt files

#### Spy on users

#### Destroy systems

#### Conduct fraud

#### Example
- The attacker steals customer databases.

#### Goal
- Achieve the purpose of the attack.

#### Memory Trick for Kill Chain

#### RWD EICA

#### R → Reconnaissance

#### W → Weaponization

#### D → Delivery

#### E → Exploitation

#### I → Installation

#### C → Command & Control

#### A → Actions on Objectives

### 2. Tactics, Techniques, and Procedures (TTPs)
- Security professionals use TTPs to understand attackers.

#### Tactics

#### Meaning
- The overall goal of the attacker.

#### Example

#### Steal data

#### Gain access

#### Maintain persistence

**Think:**

#### 👉 What is the attacker trying to achieve?

#### Techniques

#### Meaning
- The method used to achieve the goal.

#### Example

**To steal credentials:**

#### Technique = Phishing

**Think:**

#### 👉 How is the attacker doing it?

#### Procedures

#### Meaning
- The detailed step-by-step actions performed.

#### Example Procedure for Information Gathering

#### Research company

#### Find key employees

#### Collect emails

#### Identify vulnerable systems

#### Find entry points

#### Document findings

#### Why Procedures Matter

**By studying procedures, organizations can:**

#### Profile attackers

#### Predict future attacks

#### Improve defenses

#### Easy Example of TTP

#### Goal

#### Steal company data

#### Tactic

#### Credential Access

#### Technique

#### Spear Phishing

#### Procedure

#### Find employee email

#### Create fake email

#### Send attachment

#### Employee clicks

#### Malware steals password

### 3. Adversary Behavioral Identification

#### Definition
- The process of identifying common attacker behaviors.

**It helps security analysts:**

#### Predict attacks

#### Detect threats early

#### Understand attacker patterns

#### Common Adversary Behaviors

#### Internal Reconnaissance
- Attacker explores the network after gaining access.

**Example:**

**Searching for:**

#### Servers

#### Databases

#### User accounts

#### Use of Command-Line Interface (CLI)

**Attackers often use:**

#### CMD

#### Bash

#### PowerShell
- to execute commands.

#### Use of DNS Tunneling
- Attackers hide communication inside DNS traffic.

**Purpose:**

#### Bypass firewalls

#### Exfiltrate data

#### Use of PowerShell
- PowerShell is frequently abused because it is already trusted by Windows.

**Examples:**

#### Download malware

#### Execute malicious scripts

#### HTTP User-Agent Manipulation
- Attackers disguise malicious traffic as normal browser traffic.

#### Unspecified Proxy Activities
- Using proxy servers to hide attacker identity.

#### Command and Control Server Usage
- Communicating with attacker-controlled servers.

#### Use of Web Shells
- A web shell is a malicious script placed on a web server.
- It provides remote control.

#### Data Staging
- Collecting data before exfiltration.

**Example:**
- Gather files into one folder before stealing them.

#### Why Behavioral Identification is Important

**It helps security teams:**

#### ✅ Detect attacks faster

#### ✅ Identify malware activity

#### ✅ Understand attacker intentions

#### ✅ Prevent future attacks

### 4. Kill Chain Deep-Dive Scenario: Spear Phishing
- Let's see how an actual attack follows the Kill Chain.

#### Phase 1: Reconnaissance

#### Attacker Activity

**The employee posts information on:**

#### LinkedIn

#### Facebook

**such as:**

#### Job role

#### Project details

#### Interests

#### What Attacker Does

**Collects:**

#### Email address

#### Position

#### Contact information

#### Goal
- Choose the best victim.

#### Phase 2: Weaponization

#### Attacker Creates

#### Malware payload

#### Backdoor

#### Command & Control server

#### Attacker Also
- Creates a convincing phishing email.

**Example:**

#### "Project Update Document"
- with a malicious attachment.

#### Additional Step
- Tests the attachment against antivirus software.

**Goal:**
- Avoid detection.

#### Phase 3: Delivery

#### Attacker Sends
- The phishing email.

#### Result
- Email successfully passes antivirus checks.

#### Phase 4: Exploitation

#### Employee Action
- Opens the email.
- Downloads attachment.
- Double-clicks malicious file.

#### What Happens?

#### Malware executes

#### Files are installed

#### Registry keys are modified

#### Privileges are escalated

#### Indicators of Attack

#### 🚩 Suspicious attachment

#### 🚩 Password sent within email

#### 🚩 EXE file download

#### 🚩 Unknown program execution

#### Phase 5: Installation

#### Malware Installs

#### Persistence mechanisms

#### Backdoors

#### Malware Activity
- Contacts Command & Control server.
- Creates long-term access.

#### Additional Activity
- Spreads to other computers.

#### Indicators

#### 🚩 Unknown startup entries

#### 🚩 New services installed

#### 🚩 Unusual outbound traffic

#### Phase 6: Command and Control

#### Attacker Actions

**Obtains:**

#### Password hashes

#### Admin credentials

#### Establishes

**Two-way communication between:**

#### Victim ↔ C2 Server
- using HTTP.

#### Indicators

#### Connections to blacklisted domains

#### Unknown network traffic

#### Suspicious proxy activity

#### Phase 7: Actions on Objectives

#### Attacker Searches For

#### Confidential files

#### Financial data

#### Sensitive documents

#### Attacker Then

#### Collects files

#### Compresses them into RAR archives

#### Encrypts them

#### Transfers them to attacker servers

#### Indicators

#### Large RAR files

#### Excessive file access

#### Use of admin privileges

#### Data transfer to unknown domains

#### Complete Spear Phishing Kill Chain
- Employee Information Collected
                ↓
Phishing Email Created
                ↓
Email Sent
                ↓
Victim Opens Attachment
                ↓
Malware Installed
                ↓
C2 Communication Established
                ↓
Sensitive Data Collected
                ↓
Data Exfiltrated

---

## #04: Explain MITRE ATT&CK and Diamond Model

#### MITRE ATT&CK Framework

#### Definition
- MITRE ATT&CK (Adversarial Tactics, Techniques, and Common Knowledge) is a globally accessible knowledge base of adversary tactics and techniques based on real-world cyber attack observations.
- It helps security teams understand how attackers operate and improve detection, prevention, and response capabilities.

#### Key Points
- Developed by MITRE Corporation.
- Based on real-world attack behavior.
- Used by governments, private organizations, and cybersecurity vendors.
- Serves as a common language for threat intelligence and security operations.

#### ATT&CK Framework Overview

**The ATT&CK framework focuses on the later stages of the Cyber Kill Chain:**
- The framework contains 14 Enterprise Tactic Categories that describe attacker objectives during an intrusion.

#### Benefits of MITRE ATT&CK

### 1. Standardized Knowledge Base
- Provides a common reference for understanding attacker behavior.

### 2. Real-World Threat Mapping
- Maps attacks based on actual adversary techniques.

### 3. Security Improvement
- Helps organizations strengthen defenses against known attack methods.

### 4. Threat Hunting Support
- Assists analysts in proactively searching for threats.

### 5. Detection Enhancement
- Improves detection rules and monitoring capabilities.

#### Use of MITRE ATT&CK in Threat Intelligence

**MITRE ATT&CK helps threat intelligence teams by:**

#### Understand Adversary Behavior
- Study attacker tactics and techniques.
- Predict future attack patterns.

#### Visualize Adversary Footprints
- Map attacker activities across the attack lifecycle.

#### Identify Threat Groups
- Associate techniques with known threat actors and APT groups.

#### Enrich Threat Intelligence
- Add context to Indicators of Compromise (IOCs).
- Improve intelligence reports.

#### Integrate with Existing Tools

#### SIEM

#### EDR

#### Threat Intelligence Platforms

#### Security Analytics Tools

#### Use of MITRE ATT&CK in Red Teaming
- MITRE ATT&CK helps red teams perform realistic attack simulations.

#### Simulate Real-Time Attacks
- Emulate techniques used by real adversaries.

#### Ensure Coverage and Validation
- Verify security controls against known attack methods.

#### Identify Security Gaps
- Discover weaknesses in defenses.

#### Measure Security Effectiveness
- Evaluate detection and response capabilities.

#### Continual Enhancement
- Improve red team exercises over time.

#### Reporting
- Generate structured reports mapped to ATT&CK techniques.

#### Diamond Model of Intrusion Analysis

#### Definition
- The Diamond Model of Intrusion Analysis is a framework used to analyze and understand cyber intrusions by identifying relationships among different attack components.
- It helps security analysts correlate attack events and improve threat analysis.

#### Purpose
- Identify clusters of related attack events.
- Understand attacker behavior.
- Improve investigation efficiency.
- Develop effective mitigation strategies.

#### Diamond Event
- The basic unit of analysis in the Diamond Model is called a Diamond Event.

**Every intrusion can be analyzed using four core elements:**

#### Core Components of Diamond Model

### 1. Adversary (Attacker)

#### who is behind the attack (hacker, APT group)

### 2. Capability
- Tools, malware, exploits, or techniques used by the attacker.

#### Example: Ransomware, Backdoor, Exploit Kit

### 3. Infrastructure
- Resources used to launch and control attacks.

**Example:**

#### Command & Control (C2) Servers

#### Domains

#### IP Addresses

#### Hosting Services

### 4. Victim
- The target of the attack.

**Example:**

#### Organization

#### Employee

#### Government Agency

#### Individual User

#### Diamond Model Structure
- Adversary
                                     ▲
                                      │
                                      │
Capability ◄────┼────► Infrastructure
                                      │
                                      │
                                     ▼
                                 Victim

#### Extended Diamond Model of Intrusion Analysis
- The Extended Diamond Model adds additional meta-features to improve understanding of attacks.

#### Meta-Features of Extended Diamond Model

### 1. Socio-Political Meta-Feature
- Describes the relationship between the adversary and the victim.

#### Purpose
- Determines why the attack was conducted.

#### Examples

#### Cyber espionage

#### Political motives

#### Financial gain

#### Hacktivism

### 2. Technology Meta-Feature
- Connects infrastructure and capabilities.

#### Purpose

**Provides better understanding of:**

#### Communication mechanisms

#### Attack operations

#### Technology used during attacks

#### Examples

#### Operating Systems

#### Protocols

#### Cloud Services

#### Network Technologies

#### Benefits of Diamond Model

#### Better Threat Analysis
- Helps analysts understand attack relationships.

#### Event Correlation
- Links related intrusion events together.

#### Improved Threat Hunting
- Identifies attacker patterns and behaviors.

#### Faster Incident Response
- Speeds up investigation and containment.

#### Effective Mitigation
- Supports development of stronger defense strategies.

---

## #05: Understand Indicators of Compromise (IoCs)

#### Indicators of Compromise (IoCs)

#### Definition
- Indicators of Compromise (IoCs) are clues, artifacts, or pieces of forensic evidence found on a network, endpoint, or operating system that indicate a potential cyber intrusion or malicious activity within an organization's infrastructure.
- IoCs themselves are not intelligence; rather, they serve as valuable data points that help security analysts identify, investigate, and respond to cyber threats.
- Continuous monitoring of IoCs enables organizations to detect and mitigate evolving cyber threats effectively.

#### Importance of Indicators of Compromise

**IoCs play a critical role in cybersecurity because they:**

#### Detect Security Incidents
- Identify malware infections.
- Detect data breaches.
- Reveal unauthorized access attempts.

#### Improve Incident Response
- Help analysts quickly identify and contain threats.
- Reduce response time.

#### Increase Detection Accuracy
- Improve threat detection rates.
- Enhance security monitoring capabilities.

#### Support Automated Security Systems
- Feed threat information into SIEMs, IDS/IPS, EDR, and automated response platforms.

#### Help Answer Key Questions

**Security analysts use IoCs to determine:**

#### Does the file contain malicious content?

#### Has the network been compromised?

#### How did the infection occur?

#### What is the reputation/history of an IP address?

#### Categories of Indicators of Compromise

### 1. Email Indicators
- Indicators found within emails that may suggest phishing or malicious activity.

#### Examples

#### Sender's email address

#### Email subject line

#### Malicious attachments

#### Embedded links

### 2. Network Indicators
- Indicators related to network communications.

#### Examples

#### URLs

#### Domain names

#### IP addresses

#### Network connections

### 3. Host-Based Indicators
- Indicators found on endpoints or systems.

#### Examples

#### File names

#### File hashes

#### Registry keys

#### DLL files

#### Mutex objects

### 4. Behavioral Indicators
- Indicators based on suspicious activities or actions.

#### Examples

#### PowerShell execution

#### Remote command execution

#### Unusual process behavior

#### Lateral movement activities

### 5. Strategic Indicators
- High-level information regarding threat actors and campaigns.

#### Examples

#### Threat actor goals

#### Motives

#### Tactics

#### Long-term objectives

### 6. File-Based Indicators
- Indicators related to suspicious or malicious files.

#### Examples

#### Malware hashes

#### Suspicious file paths

#### Abnormal file names

#### Unexpected file sizes

#### Tampered digital signatures

#### Key Indicators of Compromise

**The following activities often indicate malicious behavior:**

#### Pyramid of Pain

#### Definition
- The Pyramid of Pain is a cybersecurity model developed by David Bianco that describes how difficult it is for an attacker to adapt when defenders detect and block different types of IoCs.

**The higher the indicator is on the pyramid:**
- The greater the impact on the attacker.
- The harder it is for attackers to change.
- The more effort is required from analysts to identify it.

#### Levels of Pyramid of Pain
- TTPs
           (Tough!)
          ----------
             Tools
        (Challenging)
          ----------
           Artifacts
          (Annoying)
          ----------
         Domain Names
           (Simple)
          ----------
         IP Addresses
            (Easy)
          ----------
         Hash Values
           (Trivial)

### 1. Hash Values (Trivial)

#### Description
- Unique cryptographic fingerprints of files.

#### Examples

#### MD5

#### SHA1

#### SHA256

#### Impact on Adversary

#### Very Low
- Attackers can easily modify a file to generate a new hash.

### 2. IP Addresses (Easy)

#### Description
- Network addresses used by attackers.

#### Examples

#### C2 Server IPs

#### Malicious Hosting IPs

#### Impact on Adversary

#### Low
- Attackers can quickly change IP addresses.

### 3. Domain Names (Simple)

#### Description
- Domains used in phishing, malware delivery, or command and control.

#### Examples

#### Fake banking websites

#### Malicious domains

#### Impact on Adversary

#### Moderate
- Requires attackers to register and configure new domains.

### 4. Network/Host Artifacts (Annoying)

#### Description
- Observable traces left behind during attacks.

#### Examples

#### Registry modifications

#### File paths

#### Scheduled tasks

#### Service creation

#### Impact on Adversary

#### High
- Attackers must significantly modify their tools and behavior.

### 5. Tools (Challenging)

#### Description
- Software or malware used by attackers.

#### Examples

#### Mimikatz

#### Cobalt Strike

#### Custom malware

#### Impact on Adversary

#### Very High
- Attackers need to develop or acquire new tools.

### 6. TTPs (Tactics, Techniques, and Procedures) (Tough!)

#### Description
- The behavior and methodology used by attackers.

#### Examples

#### Spear Phishing

#### Credential Dumping

#### Lateral Movement

#### Privilege Escalation

#### Impact on Adversary

#### Extremely High
- Changing TTPs requires altering the entire attack methodology.

#### Benefits of IoCs

#### Early Threat Detection
- Identify attacks before major damage occurs.

#### Improved Threat Hunting
- Enable proactive investigation of threats.

#### Faster Incident Response
- Reduce Mean Time to Detect (MTTD) and Mean Time to Respond (MTTR).

#### Better Threat Intelligence
- Provide valuable data for security operations and intelligence teams.

#### Enhanced Security Posture
- Strengthen organizational defenses against cyber threats.