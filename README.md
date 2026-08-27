## 🔐 Week 3: Password Cracking Labs

![Field](https://img.shields.io/badge/Field-Cybersecurity-1abc9c)
![Internship](https://img.shields.io/badge/Internship-grey)
![Week](https://img.shields.io/badge/Week-3-2ecc71)
![Topic](https://img.shields.io/badge/Topic-Password_Cracking-1a1a2e)
![Tool](https://img.shields.io/badge/Tool-John_the_Ripper-1abc9c)
![Training](https://img.shields.io/badge/Training-grey)
![Networkwalks](https://img.shields.io/badge/Networkwalks-2ecc71)

> 🔐 Hands-on password cracking labs completed during **Week 3** of my Cybersecurity Internship at NETWORKWALKS.

---

## 📌 Overview

This repository contains my **Week 3 Cybersecurity Internship labs** focused on password cracking, hash analysis, and password security.

The labs demonstrate password auditing techniques using:

- 🛠️ John the Ripper
- 🖥️ Johnny GUI
- 🌐 Networkwalks Hash Calculator
- 🔒 Networkwalks Password Cracker
- 📖 Dictionary-based attacks

> ⚠️ All activities were performed for educational purposes on authorized files and systems.

---

## 📚 Labs Completed

### 1️⃣ W3-PM1 — John the Ripper + Johnny GUI

**🎯 Objective**

Crack the password of a password-protected PDF using **John the Ripper (JTR)** and its graphical interface, **Johnny**. 

---

| Tool | Purpose |
|---|---|
| John the Ripper 1.9.0-jumbo-1 | Password cracking |
| Johnny GUI 2.2 | Graphical interface for JTR |
| PDF Hash Extractor | Extract PDF password hash |

**🚀 Methodology**

1. I used Kali Linux, so i reinstall John.
2. Downloaded Johnny GUI.
3. Configured Johnny to use `/usr/sbin/john`.
4. Extracted the PDF hash.
5. Saved the extracted hash into `hash.txt`.
6. Loaded the hash into Johnny.
7. Performed a dictionary attack.
8. Successfully recovered the password.

**✅ Result**

**Cracked Password:**

`good-luck`

**📸 Screenshots**

**01 — JTR Upgrade**

<img width="1920" height="1080" alt="Screenshot_JTR-update" src="https://github.com/user-attachments/assets/9fd047d2-8de2-44a8-a6cf-646a6a77e488" />


**02 — Johnny Installation**

<img width="1920" height="1080" alt="Screenshot_johnny-installation" src="https://github.com/user-attachments/assets/374737a3-3548-493d-a042-70bdba2aa123" />


**03 — Johnny Settings**

<img width="1920" height="1080" alt="Screenshot_johnny-setting" src="https://github.com/user-attachments/assets/2e1294fa-aa73-4537-a6bc-fa65b340b9ab" />


**04 — Hash Extracted**

<img width="1920" height="964" alt="Hash-extracted" src="https://github.com/user-attachments/assets/b0862210-2e21-4e16-94d5-f88afaecfec3" />


**05 — Password Cracked**

<img width="1920" height="1080" alt="Password-cracked" src="https://github.com/user-attachments/assets/aa1f3679-4750-45d1-8a38-159af51edbbd" />


**06 — Locked PDF**

<img width="1920" height="964" alt="Locked-pdf" src="https://github.com/user-attachments/assets/15b99861-89b0-4aaf-b98f-4889a243c7ce" />


**07 — Unlocked PDF**

<img width="1626" height="1046" alt="Unlocked-pdf" src="https://github.com/user-attachments/assets/d88ff0ef-143a-4fe6-b0ac-078e210f1b81" />

---

### 2️⃣ W3-PM2 — Networkwalks Online Tools

**🎯 Objective**

Crack the password of a password-protected PDF using **Networkwalks online security tools**.

**🛠️ Tools Used**

| Tool | Purpose |
|---|---|
| Networkwalks Hash Calculator | Generate/extract PDF hash |
| Networkwalks Password Cracker | Password security testing |

**🚀 Methodology**

1. Uploaded the PDF to the Networkwalks Hash Calculator.
2. Generated the PDF hash.
3. Copied the generated hash.
4. Pasted the hash into the Password Cracker.
5. Ran the available dictionary attack.
6. Successfully recovered the password.

**✅ Result**

**Cracked Password:**

`password1`

**📸 Screenshots**

**01 — Hash Calculator**

<img width="1490" height="974" alt="Hash-calculator" src="https://github.com/user-attachments/assets/f02684fd-8018-4c8d-9701-266bdcd5bb14" />


**02 — Password Cracker**

<img width="1373" height="1012" alt="NW- password-cracker" src="https://github.com/user-attachments/assets/ec475802-eec7-4c17-94d1-46b2e09a393c" />


**02 — Password Cracked**

<img width="1504" height="1001" alt="NW-password-cracked1" src="https://github.com/user-attachments/assets/877e99b7-5dd7-40a0-aa6a-f0b111868d6b" />



**02 — Unlocked PDF**

<img width="1409" height="1010" alt="NW_unlocked-pdf1" src="https://github.com/user-attachments/assets/e85588fc-b290-4408-b1cb-7636f4c39f41" />

---

## 🏆 Flags Captured

| Module | Flag |
|---|---|
| 🔐 W3-PM1 | `nw[cybersecurity_flag_captured_2608]` |
| 🌐 W3-PM2 | `nw{networkwalks_flag1_jtr_270521_1}` |

---

## 📂 File Descriptions

| File | Description |
|---|---|
| `W3-PM1-JTR-Johnny/hash1.txt` | PDF hash extracted for JTR |
| `W3-PM1-JTR-Johnny/cracked-password` | Password recovered using JTR |
| `W3-PM1-JTR-Johnny/screenshots/` | JTR + Johnny screenshots |
| `W3-PM2-NWTools/hash.txt` | PDF hash generated using NW Tools |
| `W3-PM2-NWTools/cracked-password.txt` | Password recovered using NW Tools |
| `W3-PM2-NWTools/screenshots/` | Networkwalks screenshots |
| `Flags` | Flags captured during the labs |

---

## 🧠 Key Learnings

### 🔑 Hashing vs Encryption

**Hashing** is generally a one-way transformation used to represent data as a fixed-length value.

**Encryption** is a reversible process where encrypted information can be decrypted using an appropriate key.

Understanding this distinction is important when studying password storage and password attacks.

### 📖 Dictionary Attacks

A dictionary attack attempts passwords from a predefined wordlist.

The labs demonstrated how predictable passwords such as:

- `password1`
- `good-luck`

can be vulnerable to dictionary-based attacks.

---

## 🛡️ Password Security Lessons

Strong passwords should:

- ✅ Be long and unique
- ✅ Use uppercase and lowercase characters
- ✅ Include numbers and special characters
- ✅ Avoid common words
- ✅ Avoid predictable patterns
- ✅ Never be reused across multiple accounts

Additional protection can be provided through:

- 🔐 Password managers
- 🔑 Multi-factor authentication
- 🛡️ Strong password policies
- 🚨 Account lockout and rate limiting

---

## 🌐 Real-World Relevance

Password-cracking techniques are useful during authorized cybersecurity assessments for:

- 🔍 Evaluating password policies
- 🛡️ Identifying weak credentials
- 📢 Security awareness and education
- 🔐 Testing password-protection mechanisms
- 🚨 Understanding attacker techniques

The purpose of ethical password auditing is to identify weaknesses **before malicious attackers can exploit them**.

---

## 💻 John the Ripper Commands

### Dictionary Attack

```
john --wordlist=rockyou.txt hash.txt
```

### Display Recovered Password

```
john --show hash.txt
```

> ⚠️ These commands should only be used against hashes and systems you are authorized to test.

---

## 🛠️ Tools & Resources

| Tool | Purpose | Link |
|---|---|---|
| John the Ripper | Password auditing and cracking | https://www.openwall.com/john/ |
| Johnny GUI | GUI for John the Ripper | https://openwall.info/wiki/john/johnny |
| Networkwalks | Cybersecurity training/tools | https://networkwalks.com/ |

---

## 📊 Lab Summary

| Lab | Tool | Attack Type | Result |
|---|---|---|---|
| W3-PM1 | JTR + Johnny | Dictionary Attack | `good-luck` |
| W3-PM2 | NW Tools | Dictionary Attack | `password1` |

---

## 📈 Skills Practiced

![Linux](https://img.shields.io/badge/Linux-1a1a2e?logo=linux&logoColor=white)
![Command Line](https://img.shields.io/badge/Command_Line-000000)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-4a4a4a)
![Password Auditing](https://img.shields.io/badge/Password_Auditing-1abc9c)
![JTR](https://img.shields.io/badge/JTR-4a4a4a)
![Password Cracking](https://img.shields.io/badge/Password_Cracking-2ecc71)
![Networking](https://img.shields.io/badge/Networking-4a4a4a)
![Security](https://img.shields.io/badge/Security-3498db)

- 🔐 Password security
- 🔍 Hash analysis
- 🛠️ John the Ripper
- 🖥️ Johnny GUI
- 📖 Dictionary attacks
- 🌐 Security tools
- 📝 Security documentation
- 📸 Technical evidence collection

---

## 🔗 Connect With Me

💼 **LinkedIn:**
[My-LINKEDIN](https://www.linkedin.com/in/your-profile/)

🐙 **GitHub:**
[My-GITHUB](https://github.com/mfonabasichosen)

---

## 🙏 Acknowledgments

Special thanks to:

**Waqas Karim (CCIE)**
Instructor & Mentor

**NETWORKWALKS**
For providing hands-on cybersecurity training and practical lab experience.

---

## ⚠️ Disclaimer

> This repository was created for educational and cybersecurity training purposes only.
>
> All password-cracking techniques demonstrated here were performed against authorized files and systems as part of a formal training environment.
>
> Unauthorized access, password cracking, or testing of systems without permission may be illegal.

---

## 🎯 Week 3 Complete!

> **Weak passwords = Easy targets. 🔐**
>
> **Learn. Test. Secure. Repeat. 🚀**
