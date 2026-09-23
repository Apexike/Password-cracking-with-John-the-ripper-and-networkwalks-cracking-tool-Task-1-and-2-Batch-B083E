# Password-cracking-with-John-the-ripper/ OnlineHashCrack-and-networkwalks-cracking-tool-Task-1-and-2-Batch-B083E
Password Cracking Project: Used John the Ripper/ OnlineHashCrack and Networkwalks together to audit password strength via offline hash cracking. JtR and Networkwalks ran dictionary, rule-based, and brute-force attacks. Weak, short, reused passwords cracked fast; strong salted hashes resisted. Recommend longer passwords, and regular audits.
 Objectives
- Assess password strength on a password-protected PDF by attempting to crack its hash.
- Identify weak or common passwords using a dictionary attack.
- Demonstrate a browser-based password cracking workflow as a simpler alternative/companion to John the Ripper.

 Purpose
To evaluate how resistant a PDF's password protection is to a dictionary attack, and to understand how browser-based tools apply the same core logic as traditional tools like JtR — hashing candidate words and comparing them to the target hash.

 Tools
- John the Ripper — command-line cracking engine; conceptually similar to Networkwalks' approach (hash + match against wordlist).
- *Networkwalks Password Cracker(networkwalks.com/password-cracker/) — a free, browser-based dictionary attack tool built by Networkwalks Academy (Cybersecurity & Ethical Hacking with AI). Hashes every word in a wordlist and matches it against a PDF's password hash — the same core idea JtR uses.
- *Networkwalks Hash Calculator — companion browser tool used to extract the $pdf$ hash from the target PDF before cracking.

Framework (Methodology)
1. Target Preparation — Have the password-protected PDF ready (e.g., My-Locked-PDF.pdf).
2. Hash Extraction— Open the Networkwalks *Hash Calculator* in browser and extract the PDF's $pdf$ hash.
3. Access the Cracker* — Navigate to networkwalks.com/password-cracker/ in browser.
4. Input the Hash — Paste the extracted $pdf$ hash into the "PDF HASH" field.
5. Choose Wordlist — Select either the built-in list (100 passwords) or upload a custom wordlist (.txt).
6.
Use of OnlineHashCrack
For hashes not cracked by the built-in tool, the same $pdf$ hash can be submitted to OnlineHashCrack as a cloud-based recovery service. It offers password strength testing and recovery, effectively running larger-scale cracking (bigger wordlists/GPU-backed attacks) than a local browser tool can handle — useful as an escalation step when simpler dictionary attacks fail.

6. 

  john the ripper/ Online hashcracker work samples
<img width="1920" height="1080" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/9f45b68d-ab20-44c9-ad86-aedeb0f7a70a" />
<img width="1920" height="1080" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/1c9b8033-e4dc-4bb5-b1ca-6193ade5a4b8" />
<img width="1920" height="1080" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/49ea4e87-7803-4fa9-9e0c-33792a073b2e" />
<img width="1920" height="1080" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/0a6098ce-d867-4163-ac6d-d882a2bf75e6" />
<img width="1920" height="1080" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/c28bf09a-d5f4-4ad7-ab03-88755ec6b5ab" />

Networkwalks password cracker
<img width="1920" height="1080" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/7e18185b-5ad7-4a84-b1f3-c88b76375c96" />
<img width="1920" height="1080" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/35cc3b3b-7e6e-4e05-8777-ca57aa2af3b8" />
<img width="1920" height="1080" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/9d9314b3-39f6-4038-869e-64b5f7e6b8d9" />
<img width="1920" height="1080" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/cf07e86b-9212-4842-b4d1-e9eb2018c8e0" />
<img width="1920" height="1080" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/86d1789a-ac89-4d1e-bee1-0c9a47a184e9" />

Linkedin:www.linkedin.com/in/ikechukwu-ogbechie-286380239

