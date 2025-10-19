# CTF-Tools

List of tools I use for CTFs and learning.

This repository is meant as a quick reference for myself and others learning cybersecurity.  
All tools listed are open-source or free for educational use.

---

## 📚 Table of Contents

- [OSINT](#osint) — Open-source intelligence, recon, data scraping  
- [Crypto](#crypto) — Encryption, encoding, hashing, math puzzles  
- [Forensics](#forensics) — File carving, memory forensics, disk analysis  
- [Misc](#misc) — Tools that don’t fit cleanly elsewhere  

---

## 🕵️ OSINT

### Google Maps

**Use Case:**  
Very useful tool when your given coordniates, addresses, or getting a address of a location.

---

### Wigle.net

**Use Case:**  
If your problem involves a WiFi network it can be useful for finding that WiFi network’s location.

---

### Etherscan.io

**Use Case:**  
Can be very useful for problems that involve the blockchain.

---

## 🔐 Crypto

### CyberChef

**What it does**  
CyberChef is a web-base tool for encryption, decryption, encoding, decoding, and other data techniques. Its a nice tool for cryptography challenges. I have also used outside of cryptography challenges since other categories can use base64 or hex encoded strings. Its also great tool for encrypted messages that have used multiple different encryption techniques on the plaintext. Cyberchef has a recipe box that allows you to input multiple encryption or decyprion techniques.

---

### dCode

**What it does**  
dCode is a decyption website that offers lots of various encyption and decryption techniques. Its a great tool for me when a certain encryption technique is not on cyberchef.

---

### HashCat

**What it does**  
Hashcat is program that cracks password hashes. It has multiple different modes of attacks along with different hashing algroithms. It can be useful if the CTF involves password cracking. HashCat is easy to use but does require a fine balancing act since certain wordlist/modes can drastically increase the time it takes to crack a hash.

---

### John the Ripper

**What it does**  
The John the Ripper is another password cracking tool but has some other use cases from hashcat. It can do the same password cracking that hascat does but helps a lot when it comes to cracking pdf passwords. John the Ripper has a tool called pdf2john that makes extracting and cracking a pdf hash easy.

---

## 🧰 Forensics

### WireShark

**What it does**  
WireShark is a packet viewing tool that also can collect packets on your local machine. Its extremely useful for network forensics problems since it tools that allow you to dig into each packet or look at the statistics of the entire packet capture. Any problem that involves a pcap is great for this tool.

---

## ⚙️ Misc

### Security Onion

**What it does:**  
Secuirty onion is a threat hunting, network security monitoring, and log management tool. Basically you setup agents on each system that send data to the machine running the secuirty onion platform. It gives you a great central observation point of what is happening on the network.

---

### Blood Hound

**What it does:**  
Blood Hound is a Active Directory anaylsis tool. It can show you relationships and attack vectors in active directory. Its a very useful tool when your team is given a network that you do not have all the knowledge of all the users on.

**Requirments**  
It does require SharpHound which scans the active directory on the network. (Note make sure to the rest of your team you are doing a scan because it will show up on other security software like security onion.)

