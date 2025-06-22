# 🧠 MITRE ATT&CK Framework

## 📚 Overview

The MITRE ATT&CK Framework is a globally used knowledge base that categorizes adversarial behavior in a structured, repeatable way. It's an essential reference for SOC Analysts, threat hunters, and red/blue teams to map, analyze, and respond to real-world cyber attacks.

Developed by MITRE, the framework helps defenders understand the “how” and “why” behind attack patterns, enabling organizations to improve detection, mitigation, and reporting.

---

## 🧱 Key Components of the Framework

### 🔷 **Matrices**
The ATT&CK Framework includes 3 matrices based on target environments:
- **Enterprise** (Windows, Linux, macOS, Cloud, Network, Containers)
- **Mobile** (Android, iOS)
- **ICS** (Industrial Control Systems)

Each matrix visualizes attacker behavior through tactics and techniques.

### 🎯 **Tactics**
Tactics represent *why* an adversary performs an action — e.g., Initial Access, Privilege Escalation, Command and Control.  
Each matrix has slightly different tactics. The Enterprise matrix includes 14 standard tactics that represent the stages of an attack.

### 🛠️ **Techniques & Sub-techniques**
Techniques explain *how* an adversary achieves a tactic (e.g., phishing, process injection).  
Sub-techniques break those down further into more specific actions. These are mapped under relevant tactics in the matrix.

### 🛡️ **Mitigations**
Each technique includes recommended **mitigations** — actions and configurations to reduce exposure or detect activity.  
Mitigations are categorized by matrix (Enterprise, Mobile, ICS) and have unique IDs and descriptions.

### 🧑‍💻 **Groups**
The framework tracks **APT groups** and the techniques/tools they are known to use (e.g., Lazarus Group). Each group is mapped to its observed behavior, helping defenders anticipate future moves.

### 💽 **Software**
The Software section lists legitimate and malicious tools used by attackers. Each entry shows which techniques the software supports and which threat groups have been seen using it.

---

## 📈 What I Learned

- How to navigate and interpret the MITRE ATT&CK matrices
- The difference between **tactics**, **techniques**, and **procedures**
- How to map real-world incidents to ATT&CK stages
- How APT groups reuse tools and techniques across campaigns
- How to apply mitigations based on specific attacker behaviors

---

## 🔗 Useful Links

- [MITRE ATT&CK Website](https://attack.mitre.org/)
- [Enterprise Matrix](https://attack.mitre.org/matrices/enterprise/)
- [Mobile Matrix](https://attack.mitre.org/matrices/mobile/)
- [ICS Matrix](https://attack.mitre.org/matrices/ics/)

> _Note: This summary is based on personal learning through practical labs and does not include any proprietary or copied content from LetsDefend.io._
