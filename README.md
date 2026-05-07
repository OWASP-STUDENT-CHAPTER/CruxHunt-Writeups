<h1 align="left">
  ⚔️ CruxHunt
  <img src="https://komarev.com/ghpvc/?username=OWASP-STUDENT-CHAPTER&repo=CruxHunt-Writeups&label=People%20Engaged&style=for-the-badge&color=blueviolet" align="right" />
</h1>

## Official CTF Writeups Repository of OWASP TIET

Welcome to the **OWASP TIET** official writeup repository.  
This repository serves as the intelligence database for solutions and methodologies used throughout the **Cruxbreaker** ecosystem. This repository is designed as a learning resource for those who fight not with spells, but with terminals and code.

Capture The Flag (CTF) competitions are a powerful way to bridge the gap between magical theory and digital reality. These challenges require problem-solving, creativity, and technical knowledge to uncover truths that are often buried deep within unsupervised infrastructure.

---

##  The Story: FIENDFYRE & The Ministry
Fifteen years ago, an engineer known only as **Snape** replaced the wizarding world's entire backend with a hybrid digital infrastructure. While the Ministry of Magic treated it as a "black box," a worm named **FIENDFYRE** was recently detected rewriting the history of the magical world. 

As part of the **Cruxbreaker Unit**, your mission was to trace this infection across five distinct stages of investigation:
*   **Round 1:** Reconnaissance in the digital "Diagon Alley".
*   **Round 2:** Infiltrating the decommissioned "Chamber B-7".
*   **Round 3:** Neutralizing the "Unforgivable" modules (Crucio, Imperius, and Avada).
*   **Round 4:** Dismantling the "Unbreakable Vow" of the core architecture.
*   **Round 5:** Following Snape’s manifesto to the final override command.

---

##  Writeups
The writeups in this repository are categorized based on the nature of the challenge and the specific mission round. Each report provides step-by-step solutions, explanations of tools used (such as Burp Suit, CyberChef, or custom exploit scripts), and the technical methodology used to retrieve the flag.


---

##  Where to Start
If you are new to the unit, we recommend starting with **Round 1 (Reconnaissance)** to understand how the infection entered the commercial layer.

*   🟢 **Easy:** Entry-level recon and metadata analysis.
*   🟡 **Medium:** Intermediate forensics and log analysis.
*   🔴 **Hard:** Complex binary exploitation and neutralizing active worm modules.
  

---


# Table of Contents

## Round 1: "Diagon Alley is Dark"
This round focuses on reconnaissance within the "commercial layer" of the wizarding world. Participants act as spies tracing the infection's entry point backward from anonymous handlers and fake vendors to identify who touched the system last.

| Q. NO. | Challenge Name | Writeup | Video Solution | Difficulty | Points | Category |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Q1**| **Doomed** | [PDF](./Writeups/Round%201/R1%20Q1.pdf) | [View](https://drive.google.com/file/d/11mRUp-rYI8yXXezvmYjWGMfyQEqN1zqX/view?usp=drive_link) | 🟢🟡 Easy-Medium | 200 | Web Exploitation / JWT / Cryptography |
| **Q2**| **The Auror’s False Name** | [PDF](./Writeups/Round%201/R1%20Q2.pdf) | [View](https://drive.google.com/file/d/1ssEAFxD23cE_xqgVZ6OMv0rY9-up2g8P/view?usp=drive_link) | 🟢 Easy | 120 | Web Exploitation |
| **Q3**| **The Disabled Gate** | [PDF](./Writeups/Round%201/R1%20Q3.pdf) | [View](https://drive.google.com/file/d/1TJ8Pk-KZeH56ly52KLv7CwtrwbN2I5Fl/view?usp=drive_link) | 🟢 Easy | 80 | Client Side HTML Manipulation |
| **Q4**| **The Borrowed Identity** | [PDF](./Writeups/Round%201/R1%20Q4.pdf) | [View](https://drive.google.com/file/d/1GjXTHI9wrIdaqOHhbofOf2GoeQ12UUR4/view?usp=drive_link) | 🟢 Easy | 120 | Broken access control and cookie manipulation |
| **Q5**| **Invisible Ink** | [PDF](./Writeups/Round%201/R1%20Q5.pdf) | [View](https://drive.google.com/file/d/1Tzxy-E7HD87yaR5idNjqVQfCtJu6ol_n/view?usp=drive_link) | 🟢 Easy | 80 | Hidden Document Metadata |
| **Q6**| **The Balanced Truthe** | [PDF](./Writeups/Round%201/R1%20Q6.pdf) | [View](https://drive.google.com/file/d/1ggQGotRJL66LychAbNa4IsqsskgQxnEU/view?usp=drive_link) | 🟢 Easy | 100 | SQL Injection |
| **Q7**| **Fragmented Challenge** | [PDF](./Writeups/Round%201/R1%20Q7.pdf) | [View](https://drive.google.com/file/d/10FbxDlsND3PORsouOBO_kHpVn2iBOLMT/view?usp=drive_link) | 🟢 Easy | 150 | Encoding |



## Round 2: "The Chamber of Systems"
The investigation moves to Chamber B-7, a decommissioned Ministry mainframe chamber that has secretly remained online for fifteen years. Using credentials recovered in Round 1, participants must explore the legacy hybrid infrastructure left behind by the engineer known as "Snape"
| Q. NO. | Challenge Name | Writeup | Video Solution | Difficulty | Points | Category |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Q1**| **The Goblin’s Hidden Path** | [PDF](./Writeups/Round%202/R2%20Q1.pdf) | [View](https://drive.google.com/file/d/1Emc5WzkOsRKWHwFQOt0KV8-HtqJwHagx/view?usp=drive_link) | 🟡 Medium | 225 | LFI & Cryptography |
| **Q2**| **The Infinite Mirror** | [PDF](./Writeups/Round%202/R2%20Q2.pdf) | [View](https://drive.google.com/file/d/1YGxjlyFedziUsuFNioxxkA_dYoAHt5OJ/view?usp=drive_link) | 🟡 Medium | 200 | Forensics / Scripting |
| **Q3**| **The Fractured Trust** | [PDF](./Writeups/Round%202/R2%20Q3.pdf) | [View](https://drive.google.com/file/d/1OIlGrWdtmTa6sVBWuAq3dzD6ycklOSjj/view?usp=drive_link) | 🟡🔴 Medium-Hard | 250 | JWT / Authentication Bypass |
| **Q4**| **The Broken Howler** | [PDF](./Writeups/Round%202/R2%20Q4.pdf) | [View](https://drive.google.com/file/d/1YVsDq-vdhDXHGfidwJGNl3AHeVvB07E_/view?usp=drive_link) | 🟢 Easy | 150 | Steganography |
| **Q5**| **The Buried Spell** | [PDF](./Writeups/Round%202/R2%20Q5.pdf) | [View](https://drive.google.com/file/d/1csqavqKohhDIKF5RKv6STFuL7DzWJUaY/view?usp=drive_link) | 🟡 Medium | 175 | Steganography & Reverse Engineering |

## Round 3: "The Unforgivable Stack"
This round shifts from reconnaissance to active combat against the three core modules of the FIENDFYRE worm, named after the Unforgivable Curses. Each module targets a different layer of the infrastructure and must be neutralized
| Q. NO. | Challenge Name | Writeup | Video Solution | Difficulty | Points | Category |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Q1**| **Sorting Hat Blocks** | [PDF](./Writeups/Round%203/R3%20Q1.pdf) | [View](https://drive.google.com/file/d/1wXCPziY470_r7hWacM4QwW28KiKMe8Ok/view?usp=drive_link) | 🟡 Medium | 270 | Web Exploitation / Cryptography / AES-ECB |
| **Q2**| **Dawlish Leak** | [PDF](./Writeups/Round%203/R3%20Q2.pdf) | [View](https://drive.google.com/file/d/1oRA2JkzEqTzqXQKD2RVVZbyNBn_gZrZt/view?usp=drive_link) | 🟡 Medium | 200 | Multi-stage OSINT + Git Forensics + Cryptography problem |
| **Q3**| **Gringotts Breach** | [PDF](./Writeups/Round%203/R3%20Q3.pdf) | [View](https://drive.google.com/file/d/1LxZ6sgVRxe3NmJRolx1FbiPTHO7ZMZGO/view?usp=drive_link) | 🔴 Hard | 300 | Cross-Site Request Forgery (CSRF) |
| **Q4**| **Riddle's Diary** | [PDF](./Writeups/Round%203/R3%20Q4.pdf) | [View](https://drive.google.com/file/d/1HVxvIzcPhYtYwCIg9DKYE5GEQMzDp8rR/view?usp=drive_link) | 🟡 Medium | 240 | Web Exploitation / SSTI / Cryptography |
| **Q5**| **Broken Cipher** | [PDF](./Writeups/Round%203/R3%20Q5.pdf) | [View](https://drive.google.com/file/d/16hGd9fYS21Diq4UzXoLHcabQPsSiJdqr/view?usp=drive_link) | 🟡 Medium | 170 | RSA/Wiener’s Attack |

## Round 4: "Breaking What Was Built to Last"
Focuses on the "Unbreakable Vow" of the system—the deepest, most architecturally resistant layers designed by Snape. This round involves dismantling complex security measures like custom instruction sets and shifting address space layouts.
| Q. NO. | Challenge Name | Writeup | Video Solution | Difficulty | Points | Category |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Q1**| **Order of the Phoenix** | [PDF](./Writeups/Round%204/R4%20Q1.pdf) | [View](https://drive.google.com/file/d/1pVvPaE82xxeX3PWrEA9EJzEVIv3bCCEG/view?usp=drive_link) | 🔴 Hard | 350 | Forensics |
| **Q2**| **Fragments of Truth** | [PDF](./Writeups/Round%204/R4%20Q2.pdf) | [View](https://drive.google.com/file/d/11uWRO6DX-3PbBvNz8nsGmfnuo9Af2KIE/view?usp=drive_link) | 🟡 Medium | 270 | Audio Forensics / Steganography  |
| **Q3**| **Example Challenge** | [PDF](./Writeups/Round%204/R4%20Q3.pdf) | [View](./path) | Medium | 310 | #Category |
| **Q4**| **The Marauder's Map** | [PDF](./Writeups/Round%204/R4%20Q4.pdf) | [View](https://drive.google.com/file/d/1twJvqyyC80_kRc-IiULa_Zy1McdrhC4z/view?usp=drive_link) | 🟡 Medium | 400 | OSINT, Digital Forensics  |

## Round 5: "Fiendfyre - The Final Cipher"
A single, two-stage investigation into Snape’s manifesto and evidence. Participants must navigate a distributed network hidden within magical portraits to recover a private key and sign a final "kill command" to release the archive lock.
| Q. NO. | Challenge Name | Writeup | Video Solution | Difficulty | Points |  Category |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Q1**| **The Portrait** | [PDF](./Writeups/Round%205/R5%20Q1.pdf) | [View](https://drive.google.com/file/d/1KpYPJ8X6vKfDmTCqpJYNVG3Gvq7mJcdj/view?usp=drive_link) | 🔴 Hard | 350 | Steganography |
| **Q2**| **The Pensive Does Not Forget** | [PDF](./Writeups/Round%205/R5%20Q2.pdf) | [View](https://drive.google.com/file/d/1ZLdq0wk7lNVX-3BH_ATBkbLt8IaQQhY0/view?usp=drive_link) | 🔴 Hard | 400 | Network Forensics / Cryptography / Steganography |

# Tools Used

Some of the tools used in these writeups include (not limited to):

| Tool Name | Link |
| :--- | :--- |
| Nmap | [https://Nmap.org/](https://Nmap.org/) |
| CyberChef | [https://gchq.github.io/CyberChef](https://gchq.github.io/CyberChef) |
| Dogbolt | [https://dogbolt.org](https://dogbolt.org) |
| Crypti | [https://cryptii.com/](https://cryptii.com/) |
| Aperi’Solve | [https://www.aperisolve.com/](https://www.aperisolve.com/) |


# Social Media Handles 

##  Connect with OWASP Thapar
Cruxbreaker is an initiative of the **OWASP Thapar Student Chapter**. Stay updated with our latest security research and upcoming CTFs:

[<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />](https://www.instagram.com/owasp_tiet/) 
[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/company/owasp-tiet/) 




