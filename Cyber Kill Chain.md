# 🧨 Cyber Kill Chain

## 📚 Overview

The Cyber Kill Chain is a framework developed by Lockheed Martin to help security teams understand the full lifecycle of a cyber attack. It breaks down the attacker’s process into 7 sequential phases — from initial reconnaissance to final impact. Understanding this model helps blue teams identify gaps in detection and implement better response strategies.

## 🔁 The 7 Stages of the Cyber Kill Chain

1. **Reconnaissance**  
   Attackers gather information about the target system using passive (e.g., public data) and active (e.g., scanning) methods. Blue teams can reduce risk at this stage by minimizing exposed info, monitoring traffic, and conducting external pentests.

2. **Weaponization**  
   The attacker creates or assembles the malware or exploit payloads based on data collected. Defenders can’t directly prevent this, but they can reduce risk by patching vulnerabilities and monitoring threat intel sources.

3. **Delivery**  
   The attacker delivers the malicious payload (e.g., via email, USB, website). Security awareness training, anti-phishing tools, and email filtering are key defenses.

4. **Exploitation**  
   The malicious code is executed on the target system. This is where initial compromise happens. Blue teams must monitor endpoints, apply security patches, and hunt for anomalies.

5. **Installation**  
   The attacker attempts to maintain persistence by installing backdoors or creating malicious services. EDR tools and behavior-based monitoring help detect these activities.

6. **Command and Control (C2)**  
   The attacker establishes remote access to the system via a C2 server. Network monitoring and threat intel can help detect or block suspicious outbound traffic.

7. **Actions on Objectives**  
   This is where the attacker's end goal is achieved — data exfiltration, ransomware encryption, destruction, or privilege escalation. DLP, access control, and anomaly detection are essential at this stage.

## 🔍 What I Learned

- How to map security events to attack stages for better incident response
- The importance of proactive defense at early stages (e.g., recon & delivery)
- Common attacker tools, techniques, and tactics at each step
- How blue teams can detect, delay, and disrupt attacks along the kill chain

## 🔧 Skills Practiced

- Analyzing simulated attacks using SIEM and threat intel tools
- Identifying delivery and exploitation attempts
- Practicing defense techniques across multiple layers of the attack
- Reviewing how each phase impacts SOC workflows

## 🌐 Reference

- [Cyber Kill Chain - Lockheed Martin](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html)

> _Note: This summary is based on personal learning through practical labs and does not include any proprietary or copied content from LetsDefend.io._
