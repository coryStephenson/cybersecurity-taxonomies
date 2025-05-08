# cybersecurity notes

- **Master Service Agreements (MSAs)** provide an umbrella contract for the work that a vendor does with an organization over an extended period of time. The MSA typically includes detailed security and privacy requirements. Each time the organization enters into a new project with the vendor, they may then create a **work order (WO)** or a **statement of work (SOW)** that contains project-specific details and references the MSA.
- **Service Level Agreement (SLA)** are written contracts that specify the conditions of service that will be provided by the vendor and the remedies available to the customer if the vendor fails to meet the SLA. SLAs commonly cover issues such as system availability, data durability, and response time.
- A **memorandum of understanding (MOU)** is a letter written to document aspects of the relationship. MOUs are an informal mechanism that allows the parties to document their relationship to avoid future misunderstandings. MOUs are commonly used in cases where an internal service provider is offering a service to a customer that is in a different business unit of the same company.
- A **memorandum of agreement (MOA)** is a formal document that outlines the terms and details of an agreement between parties, establishing a mutual understanding of the roles and responsibilities in fulfilling specific objectives. MOAs are general more detailed than MOUs and may include clauses regarding resource allocation, risk management, and performance metrics.
- **Business partners agreements (BPAs)** exist when two organizations agree to do business with each other in a partnership. For example, if two companies jointly develop and market a product, the BPA might specify each partner's responsibilities and the division of profits.  

```mermaid
graph TD;
      Cryptographic_Ciphers --> Classical_Ciphers;
      Cryptographic_Ciphers --> Modern_Ciphers;
      Classical_Ciphers --> Substitution_Ciphers;
      Classical_Ciphers --> Transpositional_Ciphers;
      Modern_Ciphers --> Secret_Cryptography;
      Modern_Ciphers --> Public_Cryptography;
      Modern_Ciphers --> Hash_Functions;
      Substitution_Ciphers --> Single_Substitution;
      Substitution_Ciphers --> Multiple_Substitution;
      Transpositional_Ciphers --> Rail_Fence_Cipher;
      Secret_Cryptography --> Block_Ciphers;
      Secret_Cryptography --> Stream_Ciphers;
      Public_Cryptography --> Integer_Factorization_Cryptosystems;
      Public_Cryptography --> Discrete_Log_Cryptosystems;
      Public_Cryptography --> Elliptic_Curve_Cryptosystems;
      Stream_Ciphers --> Synchronized;
      Stream_Ciphers --> Self_Synchronized;
      Single_Substitution --> Monoalphabetical_Ciphers;
      Monoalphabetical_Ciphers --> Atbash_Cipher;
      Atbash_Cipher --> Caesar_Cipher;
      Caesar_Cipher --> Affine_Cipher;
      Multiple_Substitution --> Polyalphabetical_Ciphers;
      Multiple_Substitution --> Polygraphic_Ciphers;
      Polyalphabetical_Ciphers --> Vigenere_Cipher;
      Vigenere_Cipher --> Gronsfield_Cipher;
      Gronsfield_Cipher --> Beaufort_Cipher;
      Beaufort_Cipher --> Auto_Key_Cipher;
      Auto_Key_Cipher --> Running_Key_Cipher;
      Polygraphic_Ciphers --> Hill_Cipher;
      Rail_Fence_Cipher --> Route_Cipher;
      Route_Cipher --> Columnar_Cipher;
      Columnar_Cipher --> Double_Transpositional_Cipher;
      Double_Transpositional_Cipher --> Myszkowiski_Cipher;
      Myszkowiski_Cipher --> Disrupted_Cipher;
      Disrupted_Cipher --> Grilles_Cipher;
      Block_Ciphers --> IDEA;
      Block_Ciphers --> DES;
      Block_Ciphers --> 3DES;
      Block_Ciphers --> AES;
      Integer_Factorization_Cryptosystems --> RSA;
      RSA --> Rabin;
      Rabin --> Schmidt-Samoa;
      Discrete_Log_Cryptosystems --> ElGamal;
      Elliptic_Curve_Cryptosystems --> ElGamal;
      ElGamal --> Cramer-Shoup;
      Cramer-Shoup --> Massey-Omura;
```

*Types of Malware*

- Spyware
- Adware
- Virus: File Infector, Boot Sector, Master Boot Record virus, Multipartite virus, Macro virus
- Worm: Email Worm, Instant Messaging Worm, Internet Worm, Internet Relay Chat (IRC) worm, File Sharing Worm
- Trojan Horse 
- Banking Trojans
- Muleware
- Doxxingware
- Cryptomalware (Ransomware)
- Grayware
- E-bomb
- Logic Bomb
- bot (botnet)
- Polymorphic malware
- Armored Malware
- Fileless Malware
- Potentially Unwanted Program (PUP)
- Keyloggers
- Backdoor
- Riskware
- Scareware
- Air-gapped malware
- Infostealers
- Rootkits
- Automated Threat
- Blended Threat
- Browser Hijacker
- Chargeware
- Code Injection (e.g. SQLI, XSS, LDAP)
- Crimeware
- Dialer
- Dropper
- File Binder
- Fleeceware
- Form Grabbing
- Malvertising
- Pharming
- Polymorphic code (uses a polymorphic engine, changes hashes for submitted malware samples)
- Pop-up Ad
- Rogue security software
- Targeted Threat
- Typhoid adware
- Virus hoax
- Webattacker
- Wiper Malware
- XARA
- Zip Bomb (a.k.a. Decompression Bomb or Zip of Death (ZOD))

*Attacks/Exploits*
- Broadcast storm
- XARA
- Zero Day Vulnerability
- Side-Channel Attacks: power consumption, timing, or electromagnetic radiation
- Phishing/Smishing/Vishing/Quishing
- Password Attacks: Brute Force, Dictionary, Spraying, Rainbow Table, Credential Harvesting, Hybrid attack, Online Password attacks, Offline password attacks
- Privilege Escalation: Kernel Exploits, Weak or Reused Credentials, App/Service Misconfiguration, Vulnerable Third-Party Software, Container Breakouts, Sudo Setup Errors, Scheduled Tasks
- Man-in-the-Middle (MitM) a.k.a on-path attacks or interception attacks
- Replay Attack: Credential Replay, Credential Stuffing 
- RFID Cloning and Skimming
- Pivoting Attack (VM Escape in the context of virtual networks)
- DDoS Attacks: Amplified (e.g. Smurf attack) and Reflected attacks
- Forgery attacks: Cross-Site Request Forgery (CSRF) and Server-Side Request Forgery (SSRF)
- Wireless Attacks: Rogue access points, Evil twin, Deauthentication (disassociation) attacks, jamming attacks, MAC spoofing, device impersonation
- ARP Poisoning
- Session Replay: Cross-Site Scripting (XSS)

*SQL Injection Attacks*
- Blind content-based SQL injection
- Blind SQL injection
- Blind timing-based SQL injection
  
*DNS Attacks*
- DNS Hijacking
- DNS Cache Poisoning (a.k.a. DNS spoofing)
- DNS Amplification
- DNS Tunneling
- DNS Flooding
- Subdomain Attack
- Domain Generation Algorithm Attack
- DNS Rebinding
- NXDOMAIN Attack
- DNSSEC Bypass

*Cryptographic Attacks*
- Downgrade Attacks: SSL/TLS downgrade, SSL stripping
- Collision Attack
- Birthday Attack
- Pass-the-Hash Attack
- Meet-in-the-Middle (MitM)

*Ransomware*
- big-game-hunting ransomware
- commodity ransomware
- extortionware
- double extortion
- triple extortion
- Ransomware-as-a-Service (RaaS)
- "grey infrastructure"/bulletproof servers

<a href="https://www.researchgate.net/figure/Classification-of-cryptographic-algorithms_fig4_330440535"><img src="https://www.researchgate.net/profile/Ki-Hyun-Jung/publication/330440535/figure/fig4/AS:715946696122370@1547706402764/Classification-of-cryptographic-algorithms.ppm" alt="3 Classification of cryptographic algorithms."/></a>

[https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-78-5.pdf](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-78-5.pdf)
