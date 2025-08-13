# DOOMLIST
This is a  wordlist for Africa  
# Nigerian Wordlist for Ethical Hacking

This repository contains Nigerian-specific password and wordlists for ethical hacking, penetration testing, and CTF challenges.

## 📂 Structure
- **passwords/** → Common Nigerian passwords, slang, seasonal events, sports, politics.
- **usernames/** → Popular Nigerian first names & celebrities.
- **wordlists/** → Targeted sectors like banks, telcos, schools, and places.
- **generators/** → Scripts to generate custom patterns.

## ⚠️ Legal Disclaimer
This wordlist is for authorized security testing and educational purposes only.
Do not use it for unauthorized activities.

## 🇳🇬 Features
- Includes Nigerian slang, cultural terms, and seasonal events.
- Useful for password cracking, fuzzing, and CTFs.

## 🛠 Example Use
```bash
hydra -L usernames/common.txt -P passwords/common.txt ssh://target.com
