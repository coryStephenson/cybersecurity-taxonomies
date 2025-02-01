# cybersecurity notes

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
- Virus
- Worm
- Trojan Horse (Remote Access Trojan)
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
- Polymorphic code (uses a polymorphic engine)
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
- XARA
- Zero Day Vulnerability
- Side-Channel Attacks: power consumption, timing, or electromagnetic radiation
- Phishing/Smishing/Vishing/Quishing
- Password Attacks: Brute Force, Dictionary, Spraying, Rainbow Table, Credential Harvesting, Hybrid attack, Online Password attacks, Offline password attacks
- Privilege Escalation: Kernel Exploits, Weak or Reused Credentials, App/Service Misconfiguration, Vulnerable Third-Party Software, Container Breakouts, Sudo Setup Errors, Scheduled Tasks
- Meet-in-the-Middle (MitM)
- Man-in-the-Middle (MitM) a.k.a on-path attacks or interception attacks
- Replay Attack: Credential Replay, Credential Stuffing 
- RFID Cloning and Skimming
- Pivoting Attack (VM Escape in the context of virtual networks)
- DDoS Attacks: Amplified (e.g. Smurf attack) and Reflected attacks
- Forgery attacks: Cross-Site Request Forgery (CSRF) and Server-Side Request Forgery (SSRF)
- Wireless Attacks: Rogue access points, Evil twin, Deauthentication (disassociation) attacks, jamming attacks, MAC spoofing, device impersonation
- ARP Poisoning
- Session Replay: Cross-Site Scripting (XSS)

*Cryptographic Attacks*
Downgrade Attacks: SSL/TLS downgrade, SSL stripping
Collision Attack
Birthday Attack
Pass-the-Hash Attack


<a href="https://www.researchgate.net/figure/Classification-of-cryptographic-algorithms_fig4_330440535"><img src="https://www.researchgate.net/profile/Ki-Hyun-Jung/publication/330440535/figure/fig4/AS:715946696122370@1547706402764/Classification-of-cryptographic-algorithms.ppm" alt="3 Classification of cryptographic algorithms."/></a>

[https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-78-5.pdf](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-78-5.pdf)
