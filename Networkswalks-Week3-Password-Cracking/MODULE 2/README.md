
Module 2: Hash Password Cracking Using John the Ripper

Objective

To understand password hash cracking using John the Ripper (JtR) and perform a dictionary-based password attack in a controlled lab environment.

Tools Used

- Kali Linux
- John the Ripper
- RockYou Wordlist
- Terminal

Procedure

Step 1: Navigate to Downloads

cd /home/kali/Downloads

Step 2: Crack the PDF Password Hash

Used John the Ripper with the RockYou wordlist to identify the password from the extracted hash.

john --wordlist=/usr/share/wordlists/rockyou.txt hash1.txt

Step 3: Display the Cracked Password

john --show hash1.txt

Screenshots

Screenshot 1: Password Hash Cracking

<img width="1600" height="768" alt="MODULE-2-Hash-Calculator" src="https://github.com/user-attachments/assets/cbeeb9b6-9f5d-4152-bbc8-08bdacb75f9f" />


Screenshot 2: Displaying the Cracked Password

<img width="1600" height="768" alt="MODULE-2-Password-cracker" src="https://github.com/user-attachments/assets/7c94ff67-a2fa-4dd1-95af-20279f97d327" />


Result

Successfully performed dictionary-based password cracking using John the Ripper and verified the recovered password using the "john --show" command.

Learning Outcome

- Understood password hashing.
- Learned dictionary-based password attacks.
- Gained practical experience with John the Ripper.
- Understood the importance of strong passwords.

---

Author

Dharshini R P

"LinkedIn" (https://www.linkedin.com/in/iamdharshini/)
