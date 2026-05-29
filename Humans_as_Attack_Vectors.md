# Social Engineering

## Definition

A phishing attack is when someone tries to trick you into sharing your private information, like passwords or credit card numbers. They do this by sending fake messages, usually pretending to be a bank, a company, or someone you trust. These messages look real, but they are fake. If you click on a link or give your details, the attacker can steal your money or private information. 
It's like a fake trap that tries to fool you into giving away your secrets.

## Objective

- Steal credentials
- Gain unauthorized access
- Collect sensitive information
- Bypass security controls

## Common Techniques

### Phishing

Sending fake emails or websites to trick victims into revealing information.

### Vishing

Voice-based phishing through phone calls.

### Smishing

Phishing through SMS messages.

## Red Flags

- Urgent requests
- Suspicious links
- Unknown senders
- Requests for passwords

## SOC Interview Question

### What is Social Engineering?

Social engineering is the psychological manipulation of people to disclose confidential information or perform actions that compromise security.

## Quick Notes

| Point | Description |
|---------|------------|
| Target | Humans |
| Goal | Information Theft |
| Common Attack | Phishing |
| Prevention | Awareness Training |

Certainly! Here's a detailed explanation of detection and mitigation applicable across various cybersecurity threats:

---

### Detection

**Definition:**  
Defending against threats involves two key tasks: Mitigation and Detection. Mitigation aims to prevent or reduce the chance and impact of attacks, for example by training employees or deploying a good anti-phishing solution. However, no matter how good mitigation measures are, one day they are bypassed. That's where your SOC skills are vital to detect and investigate advanced attacks that slip through:
Detection is the process of identifying potential security threats, unauthorized activities, or malicious behavior within a system, network, or application. It involves continuous monitoring and analysis to recognize signs of an attack or breach as early as possible.

**Key Components of Detection:**  
1. **Monitoring and Logging:**  
   - Collecting data from system logs, network traffic, and application activity.  
   - Tools like Security Information and Event Management (SIEM) systems aggregate and analyze logs for suspicious patterns.

2. **Intrusion Detection Systems (IDS) and Intrusion Prevention Systems (IPS):**  
   - IDS detects potential threats by comparing activity against known attack signatures or behavioral patterns.  
   - IPS can actively block or prevent detected threats in real-time.

3. **Anomaly Detection:**  
   - Identifies deviations from normal behavior, such as unusual login times, data transfers, or system access.  
   - Machine learning algorithms can enhance anomaly detection by learning typical activity patterns.

4. **Threat Intelligence Feeds:**  
   - Integrate external data about emerging threats and attack indicators to enhance detection capabilities.

5. **User Behavior Analytics (UBA):**  
   - Monitors user activities for abnormal actions that could indicate insider threats or compromised accounts.

**Examples:**  
- Detecting multiple failed login attempts indicating brute-force attacks.  
- Recognizing data exfiltration by monitoring large outbound data transfers.  
- Identifying malware communications with command-and-control servers through network analysis.

---

### Mitigation

**Definition:**  
Mitigation involves taking proactive and reactive steps to reduce the risk, contain, or eliminate security threats and minimize damage. It aims to prevent future incidents and ensure business continuity.

**Key Components of Mitigation:**  
1. **Preventive Measures:**  
   - Implementing firewalls, antivirus, and anti-malware solutions.  
   - Enforcing strong password policies and multi-factor authentication (MFA).  
   - Regularly applying security patches and updates to software and systems.

2. **Incident Response Planning:**  
   - Developing clear procedures for responding to different types of threats.  
   - Ensuring rapid containment, eradication, and recovery.

3. **Network Segmentation:**  
   - Dividing the network into segments to limit the spread of malware or intrusions.  
   - Isolating critical systems from less secure parts of the network.

4. **Data Backup and Recovery:**  
   - Regularly backing up data to enable restoration after an attack like ransomware.  
   - Ensuring backups are stored securely and tested periodically.

5. **Real-time Response Actions:**  
   - Automatically blocking malicious IP addresses or user accounts.  
   - Quarantining infected systems to prevent further spread.

6. **User Education and Awareness:**  
   - Training users to recognize and avoid phishing, social engineering, and unsafe practices.  
   - Promoting a security-conscious culture.

**Examples:**  
- Isolating affected systems immediately after detecting malware.  
- Blocking malicious IP addresses detected during intrusion attempts.  
- Applying patches to fix known vulnerabilities exploited by attackers.  
- Conducting forensic analysis to understand the attack vector and improve defenses.
