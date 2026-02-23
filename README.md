# Camphish
# CamPhish

## 📌 Overview

CamPhish is a cybersecurity research and educational project designed to demonstrate how camera phishing attacks can be structured in controlled environments.

The tool simulates social engineering techniques where victims are tricked into granting camera access via deceptive web pages. This project is intended strictly for cybersecurity awareness, penetration testing training, and ethical research purposes.

⚠️ This tool must only be used in authorized lab environments.

---

## 🎯 Purpose

The objective of CamPhish is to help security learners understand:

- How social engineering attacks target user permissions
- How browser camera access can be exploited
- How attackers disguise malicious intent
- Why user awareness and permission control are critical
- How to defend against camera-based phishing attacks

---

## 🚀 Features

- Pre-built camera phishing page templates (for demonstration)
- Lightweight shell-based architecture
- Tunnel support for lab-based remote testing
- Automated setup scripts
- Minimal dependency requirements

---
# Installing and requirements
<p>This tool require PHP for webserver, and wget for downloading dependencies. First run following command on your terminal</p>

```
apt-get -y install php wget unzip
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/techchipnet/CamPhish
cd CamPhish
bash camphish.sh
```

## Clean logs & unnecessary files :

```
bash cleanup.sh
```
<p>The cam files and saved location will also be removed.</p>

---

## 🔒 Ethical Use Policy

- This project is strictly for:

- Educational demonstrations

- Cybersecurity training

- Authorized penetration testing

- Security awareness workshops

🚫 Unauthorized access to devices or cameras is illegal.
🚫 Misuse of this tool may violate privacy and cybersecurity laws.

By using this software, you agree to take full responsibility for your actions.  

---

## 🛡️ Defensive Awareness

- To protect against camera phishing:

- Do not grant camera permissions to unknown websites

- Always verify URLs before interacting

- Use updated browsers

- Enable permission prompts

- Use endpoint protection tools

---

### CamPhish is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.
### Unauthorized reuploading of this project is prohibited.
