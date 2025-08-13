# Doomlist – African Wordlist & Password Collection

🚨 **ETHICAL HACKING ONLY – READ THIS FIRST** 🚨  
Doomlist is provided **strictly for authorized security testing, red teaming, and educational purposes**.  
If you use this for any **unauthorized access, fraud, or illegal activity**, you are **breaking the law** and you alone will be responsible.  
The maintainers do **NOT** condone or take responsibility for misuse.  
Always ensure you have **written permission** before using these lists.

---

## 📌 Overview
Doomlist is a **specialized African-focused wordlist collection** for ethical hacking, penetration testing, and CTF challenges.  
It contains African names, common passwords, usernames, and sector-specific terms gathered from cultural, linguistic, and OSINT research.  
It is designed to **mimic real-world patterns** used in Africa, making it highly effective for targeted security assessments.

---

## 📂 What’s Inside
- **usernames/** – African first names, surnames, celebrity names, slang-based usernames.
- **passwords/** – Common African passwords, slang terms, seasonal events, sports teams, political references.
- **wordlists/** – Banks, telcos, universities, and place names across Africa.
- **common_list/** – Shortlists of the most frequently seen credentials.
- **hashes/** – Example hashes for password cracking practice.
- **generators/** – Python scripts to generate custom usernames & passwords from templates and patterns.

---

## 🛠 Uses
When authorized, Doomlist can be used for:
- Brute-forcing **Wi-Fi passwords** (WPA/WPA2 handshakes)
- Cracking **Gmail** or email logins during red team ops
- Testing **web application login forms**
- Auditing **SSH, FTP, and database credentials**
- Simulating **phishing campaign credential guessing**

Supported tools:
- Hydra
- John the Ripper
- Aircrack-ng
- Hashcat
- Medusa
- Burp Suite Intruder

---

## 📜 Example Usage

Hydra (SSH brute-force):
```bash
hydra -L usernames/nigeria_common.txt -P passwords/nigeria/common.txt ssh://target.com
