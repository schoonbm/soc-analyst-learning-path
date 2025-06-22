# 🎣 Phishing Email Analysis

## 📚 Overview

Phishing is one of the most common initial access techniques used by attackers. This section focused on how phishing fits into the Cyber Kill Chain, and provided practical skills for identifying, investigating, and mitigating phishing threats. I learned how to analyze email headers, identify spoofed emails, perform static and dynamic analysis, and use threat intelligence tools like VirusTotal and Talos Intelligence.

---

## 🧪 Skills Practiced

- Identifying spoofed emails using **SPF, DKIM, and DMARC** checks
- Analyzing **email headers** to detect suspicious routes or forged sender info
- Using **MXToolbox**, **Whois**, and **Talos** to verify mail servers and IP reputations
- Performing **static and dynamic analysis** on phishing URLs and attachments
- Detecting phishing patterns such as:
  - Mismatched "From" and "Reply-To"
  - Hidden malicious links in HTML
  - Use of trusted platforms (e.g., Google Forms, Drive) for social engineering

---

## 🛠️ Tools Used

- **VirusTotal** – URL and file reputation
- **AbuseIPDB** – IP abuse history
- **Cisco Talos** – Domain and IP intelligence
- **MXToolbox** – Email authentication record checker
- **Browserling** – Secure browser sandbox for link inspection
- **Joe Sandbox**, **Any.Run**, **Hybrid Analysis** – Dynamic malware sandboxes

---

## 🔍 Detection Techniques

- **Header inspection** to detect spoofed domains and mail relays
- **Reputation lookups** for suspicious IPs and URLs
- **Hover-over link testing** to spot deceptive hyperlinks
- **Payload analysis** in a sandbox environment to simulate malicious behavior
- **URL parameter tracking** to identify email harvesting attempts

---

## 🧠 What I Learned

- How to identify red flags in email headers and sender behavior
- Why attackers often abuse trusted platforms to bypass filters
- How phishing analysis ties into incident response workflows
- The importance of verifying the source of suspicious attachments and URLs
- How to use multiple tools to enrich and verify email-based IOCs

---

> _Note: This summary is based on personal learning through practical labs and does not include any proprietary or copied content from LetsDefend.io._
