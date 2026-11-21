# 🔐 Password Cracking – Cybersecurity & Ethical Hacking

## 📌 Project Overview

This repository documents my hands-on cybersecurity practical exercises focused on **Password Cracking and Password Security**.

The project explores how security professionals use password-cracking tools to assess password strength, understand password hashes, and demonstrate the security risks associated with weak passwords.

The practical exercises involved recovering the password of a protected PDF file using two different approaches.

## 🎯 Project Objectives

- Understand how password cracking works.
- Learn the difference between encryption and hashing.
- Extract password hashes from protected PDF documents.
- Perform dictionary attacks using password-cracking tools.
- Understand the importance of strong password policies.
- Gain practical experience with ethical hacking tools.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| John the Ripper (JTR) | Password hash cracking |
| Johnny GUI | Graphical interface for John the Ripper |
| Networkwalks Hash Calculator | Extracting password hashes from protected PDF files |
| Networkwalks Password Cracker | Recovering passwords through dictionary attacks |
| Windows 10 / Kali Linux | Testing environments |
| Notepad | Saving extracted password hashes |

## 📚 Project Modules

### Module 1: Password Cracking with John the Ripper (JTR)

**Objective:** Recover the password of a protected PDF document using John the Ripper and Johnny GUI.

**Practical Tasks:**

1. Download and install John the Ripper.
2. Install and configure Johnny GUI.
3. Locate and configure the `john.exe` executable.
4. Extract the password hash from the protected PDF.
5. Save the extracted hash in a `.txt` file.
6. Import the hash into Johnny GUI.
7. Start a password-cracking attack.
8. Recover the password and use it to access the protected PDF.

**Tools Used:**
- John the Ripper
- Johnny GUI
- Online PDF Hash Extractor

### Module 2: Password Cracking with Networkwalks Tools

**Objective:** Recover the password of a protected PDF using Networkwalks online cybersecurity tools.

**Practical Tasks:**

1. Download the encrypted PDF file.
2. Open the Networkwalks Hash Calculator.
3. Upload the protected PDF to extract its password hash.
4. Copy the complete hash value.
5. Open the Networkwalks Password Cracker.
6. Paste the extracted hash.
7. Execute a dictionary attack.
8. Retrieve the recovered password.
9. Open the protected PDF using the recovered password.

**Tools Used:**
- Networkwalks Hash Calculator
- Networkwalks Password Cracker

## 🧠 Key Concepts Learned

**1. Password Cracking**

Understanding how password-cracking tools attempt to recover passwords from stored password hashes.

**2. Hashing**

Learning how plaintext passwords are transformed into hash values and how these values can be tested against password guesses.

**3. Dictionary Attacks**

Understanding how cracking tools compare candidate passwords against a target hash until a match is found.

**4. Encryption vs Hashing**

- Encryption is reversible using the appropriate decryption key.
- Hashing is designed as a one-way transformation.

**5. Password Security**

Understanding why short, predictable, and commonly used passwords are vulnerable to password-cracking attacks.

## 💡 Key Takeaways

Through these practical exercises, I gained experience with:

- Password hash extraction.
- Password recovery techniques.
- Dictionary-based password attacks.
- John the Ripper and Johnny GUI configuration.
- Browser-based password-cracking tools.
- Identifying weaknesses in password security.

The exercises reinforced an important cybersecurity lesson: **strong, unique passwords are essential for protecting sensitive information.**

## ⚖️ Ethical Considerations

These exercises were conducted for educational purposes in a controlled learning environment.

Password-cracking techniques should only be performed on files, systems, and password hashes that you own or have explicit authorization to test.

## 🚀 Conclusion

This project strengthened my practical understanding of password security and ethical hacking. It also provided an opportunity to explore different password-cracking tools and understand how security professionals assess password vulnerabilities.

**Learning. Practising. Securing.**

---

**#Cybersecurity #EthicalHacking #JohnTheRipper #PasswordCracking #NetworkSecurity #InformationSecurity**
