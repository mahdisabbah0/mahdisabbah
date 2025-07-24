# 🔐 Hashcat Labs

This folder contains my practical notes and examples using **Hashcat**, a powerful password recovery tool. The exercises simulate real-world scenarios in which hashed passwords are cracked using dictionary and brute-force attacks.

## 🧪 What’s Included

- Sample hashed password lists
- Dictionary file samples
- Hashcat command references and syntax
- Screenshots of cracked hashes using different modes

## 🛠️ Tools & Techniques

- Hash formats: MD5, SHA1
- Attack modes: Straight, Combinator, Brute-force
- Wordlist and rules usage

## 📚 Learning Goals

- Understand how hashed passwords can be targeted
- Explore ethical password cracking methodologies
- Apply security practices to prevent such vulnerabilities


## ✅ Sample Command
5f4dcc3b5aa765d61d8327deb882cf99
202cb962ac59075b964b07152d234b70


::::hashcat -m 0 -a 0 -o cracked.txt hashes.txt /usr/share/wordlists/rockyou.txt
