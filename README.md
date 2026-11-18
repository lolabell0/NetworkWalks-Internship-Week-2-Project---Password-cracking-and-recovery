# 🔐 Password Cracking & Recovery Report

**W3-PM-FINAL | Cybersecurity | Networkwalks**

![Cybersecurity](https://img.shields.io/badge/Field-Cybersecurity-blue)
![Program](https://img.shields.io/badge/Program-Networkwalks-green)
![Week](https://img.shields.io/badge/Week-03-orange)
![Purpose](https://img.shields.io/badge/Purpose-Education%20%26%20Research-lightgrey)

---

## 📌 Project Information

| Field | Details |
|---|---|
| **Pentester Name** | Damilola Bello (Cybersecurity Professional) |
| **Program / Batch** | B084 – Networkwalks |
| **Program Name** | Cybersecurity Program at Networkwalks |
| **Week** | 03 |
| **Date** | 18 November 2026 |
| **Modules Completed** | W3-PM1 (Password recovery with JTR), W3-PM2 (Password recovery with NW Tools) |
| **Client / Target** | Networkwalks |
| **Permission secured from client?** | ✅ Yes (written permission secured) |
| **Phases Covered** | Phase 1: Hash Calculation, Phase 2: Password Cracking |

---

## 📑 Table of Contents

1. [Liability Disclaimer](#1-liability-disclaimer)
2. [Introduction](#2-introduction)
3. [Tools Used](#3-tools-used)
4. [Activities Performed](#4-activities-performed)
5. [Risk Analysis / Impact](#5-risk-analysis--impact)
6. [Recommendations](#6-recommendations)
7. [Conclusion](#7-conclusion)
8. [Evidence Collected](#8-evidence-collected)
9. [Author](#author)

---

## 1. Liability Disclaimer

> I have performed these activities only on systems and devices where I had secured written permission, or on devices and systems that I own myself. All materials in this repository are for **education and research purposes only**.

---

## 2. Introduction

This report covers cracking and recovering weak passwords of locked PDF files using **John the Ripper** and **Networkwalks free tools**.

- **One module** uses an online hash calculator and John the Ripper.
- **The other module** uses the Networkwalks Hash Calculator to take the hash out of a locked PDF file, then the Networkwalks Password Cracker to find the real password from that hash.

Together they show how password cracking works step by step and why strong passwords are important for protection.

Every step includes the exact command used, the result observed, a screenshot as evidence, and a short note on why the finding matters from an attacker's point of view.

---

## 3. Tools Used

| Tool | Purpose |
|---|---|
| PDF Hash Extractor | Find the hash value of the encrypted PDF |
| John the Ripper | Crack the PDF password from the hash value |
| Networkwalks Hash Calculator | Find the hash value of the encrypted PDF |
| Networkwalks Password Cracker | Crack the PDF password from the hash value |

---

## 4. Activities Performed

### 4.1 Hash Calculation

Using [OnlineHashCrack PDF Hash Extractor](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php) and the [Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator/), I performed a hash calculation of the encrypted PDF files.

### 4.2 Password Cracking

For the second phase, I used **John the Ripper (JTR)** and the **Networkwalks Password Cracker** to recover the passwords of the encrypted files from the hash values.

After completing the attack, the password was revealed.

---

## 5. Risk Analysis / Impact

Based on the activities, I identified the following potential risk.

| # | Risk / Finding | Evidence / Observation | Potential Impact | Risk Level |
|---|---|---|---|---|
| 1 | Weak Passwords | Easily identifiable passwords made the encrypted files easily accessible | Attackers can easily get into confidential information when the password is weak and common | 🔴 Critical |

**Risk level key:** 🔴 Critical | 🟠 Medium | 🟢 Low

---

## 6. Recommendations

Based on the observations from these activities, I recommend the following security improvements:

1. **Review passwords**
   Organizations should use strong passwords consisting of letters, numbers and symbols.
2. **Keep passwords updated**
   Passwords should be regularly updated and reviewed against current security advisories.
3. **Perform regular internal scans**
   Organizations should periodically scan their own passwords and review how easily they can be cracked.

---

## 7. Conclusion

During Week 3 of my Cybersecurity & Ethical Hacking internship, I completed practical activities covering password cracking and recovery.

I used two different methods to crack the passwords:

- An **online hash calculator** and the **Networkwalks Hash Calculator** to take the hash out of a locked PDF file.
- **John the Ripper** and the **Networkwalks Password Cracker** to recover the password from the hash value.

The exercises showed me that using strong and complex passwords is an important part of cybersecurity. Regularly reviewing passwords and running internal scans is also necessary.

---

## 8. Evidence Collected

### Using Online Hash Calculator and JTR

![JTR Evidence 1](images/jtr-evidence-1.png)
![JTR Evidence 2](images/jtr-evidence-2.png)

### Using Networkwalks Tools

![Networkwalks Evidence 1](images/networkwalks-evidence-1.png)
![Networkwalks Evidence 2](images/networkwalks-evidence-2.png)

---

## Author

**Damilola Bello**
Cybersecurity Professional, B084
🔗 [LinkedIn](https://www.linkedin.com/in/damilolabelloo/)

---

*Program: Cybersecurity Program at Networkwalks | Week 03*
