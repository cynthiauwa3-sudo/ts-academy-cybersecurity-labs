# Module 01: Cybersecurity Foundations, Threat Landscape & OSINT Hygiene

Welcome to the first entry of my hands-on cybersecurity journey at **TS Academy**. Rather than just taking notes, I am documenting how I apply core security concepts in practice—starting with foundational defense, threat modeling, and Open-Source Intelligence (OSINT) verification.

---

## 🧠 Core Concepts & What I Learned

* **Zero-Trust Mindset ("Never Trust, Always Verify"):** Cybersecurity starts with everyday habits—never blindly clicking links, using unique passwords across every account, rotating credentials regularly (at least every 3 months), and keeping software/patches up to date to close known vulnerabilities.
* **The CIA Triad vs. The DAD Triad:** Every security control protects **Confidentiality**, **Integrity**, and **Availability**. When those controls fail, systems fall into the **DAD Triad**:
  * **Disclosure** (Confidentiality breached—unauthorized parties see sensitive data)
  * **Alteration** (Integrity breached—data is tampered with or modified)
  * **Denial** (Availability breached—legitimate users are locked out of systems or services)
* **Threat Actors & Attackers:** Learned the difference between **White Hat** (ethical defenders), **Grey Hat**, and **Black Hat** hackers, alongside real-world threat profiles including **Script Kiddies**, **Hacktivists**, **Cybercriminals**, **State-Sponsored Actors**, and **Advanced Persistent Threats (APTs)**.

---

## 🛠️ Hands-On Practical Labs

### 1. Credential Exposure Audit with *Have I Been Pwned*
* **Objective:** Check whether my personal email address has ever been exposed in a known third-party data breach (which would represent a **Confidentiality / Disclosure** failure).
* **Execution & Findings:** I queried my email address on [Have I Been Pwned](https://haveibeenpwned.com/) and confirmed **0 Data Breaches**—meaning my credentials have not appeared in any publicly indexed breach datasets.
* **Security Takeaway:** Even with zero breaches found, proactive monitoring, strong unique passwords, and Multi-Factor Authentication (MFA) remain essential so a single leaked database never compromises multiple accounts.

<img width="1920" height="1080" alt="Screenshot (108)" src="https://github.com/user-attachments/assets/d958be55-76c6-46f9-83fa-a83cbd3151b1" />


### 2. URL Reputation & Malware Analysis with *VirusTotal*
* **Objective:** Verify whether an unfamiliar URL is safe or flagged as malicious before interacting with it.
* **Execution & Findings:** Prior to this class, I didn't realize anyone could inspect suspicious links across dozens of antivirus engines and security scanners in seconds using [VirusTotal](https://www.virustotal.com/). Testing URLs here showed me how defenders check domain reputation and vendor detections before clicking.
* **Security Takeaway:** Never rely on visual inspection alone to judge a link—always verify URLs through threat intelligence tools first.

<img width="1920" height="1080" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/db4db83e-7797-43d1-aea6-324076d4c290" />
