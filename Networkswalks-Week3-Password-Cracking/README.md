Networkwalks Week 3 – Password Cracking

Cybersecurity Internship | Batch B084E

1. Project Overview

As part of Week 3 of my Networkwalks Cybersecurity Internship, I performed practical exercises related to PDF password security and password recovery.

The activities focused on PDF hash extraction, dictionary attacks, wordlist testing, and browser-based password recovery tools.

2. Module 1 – Password Cracking Using John the Ripper (JTR)

Objective

To understand PDF password hash extraction and password cracking using John the Ripper in Kali Linux.

Tools Used

- Kali Linux
- John the Ripper
- pdf2john
- rockyou.txt wordlist
- Oracle VirtualBox

Steps Performed

1. Verified the John the Ripper installation.
2. Located the password-protected PDF file.
3. Extracted the PDF hash using "pdf2john".
4. Saved the extracted hash in "hash1.txt".
5. Used the "rockyou.txt" wordlist to perform a dictionary attack.
6. Verified the result using "john --show".

Commands Used

1. Verify John the Ripper

john

2. Locate pdf2john

locate pdf2john

3. Extract the PDF hash

pdf2john "My Locked PDF1.pdf" > hash1.txt

4. Perform dictionary attack

john --wordlist=/usr/share/wordlists/rockyou.txt hash1.txt

5. Display the cracking result

john --show hash1.txt

Practical Screenshots

1. John the Ripper Version

<img width="1600" height="768" alt="MODULE-1-01-JTR-Version" src="https://github.com/user-attachments/assets/f79c6539-e0a2-4a6e-8ec5-c0869c3fadbb" />


2. PDF Hash Extraction

<img width="1600" height="768" alt="MODULE-1-02-PDF-Hash-Extraction" src="https://github.com/user-attachments/assets/45b17e6b-14ec-4704-9391-d578937ed36d" />


3. Successful Password Cracking Result

<img width="1600" height="768" alt="MODULE-1-03-Success-Result" src="https://github.com/user-attachments/assets/182f0c0c-9a70-4c04-b23a-eb483c510527" />


Result

Successfully cracked the password of the test PDF using John the Ripper and verified the result.

3. Module 2 – Password Cracking Using Networkwalks Online Tools

Objective

To practise PDF hash generation and password recovery using Networkwalks online tools.

Tools Used

- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Firefox Browser

Steps Performed

1. Opened the Networkwalks Hash Calculator.
2. Uploaded the password-protected PDF file.
3. Generated a crackable PDF hash.
4. Copied the generated hash.
5. Opened the Networkwalks Password Cracker.
6. Submitted the hash and started the password recovery process.
7. Tested the available built-in wordlist.

Practical Screenshots

1. PDF Hash Generation

<img width="1600" height="768" alt="MODULE-2-Hash-Calculator" src="https://github.com/user-attachments/assets/4362085b-70e4-4969-b4c7-d136c9c2498b" />


2. Password Cracker Result
<img width="1600" height="768" alt="MODULE-2-Password-Cracker" src="https://github.com/user-attachments/assets/4941fe95-ef4f-42b3-94e7-b066629e4240" />



Result

Successfully generated a PDF hash using the Networkwalks Hash Calculator. The initial built-in wordlist containing 100 passwords did not find a match. This exercise provided practical experience with browser-based hash generation and wordlist-based password testing.

4. Key Learning Outcomes

- Understood PDF password protection and hash extraction.
- Learned the working process of John the Ripper.
- Practised dictionary-based password attacks.
- Gained experience in PDF hash generation.
- Explored browser-based password recovery tools.
- Understood the importance of strong password security.

5. Conclusion

The Week 3 practical exercises provided hands-on experience with PDF password security and password recovery techniques using John the Ripper and Networkwalks online tools.

These activities improved my understanding of hash extraction, dictionary attacks, wordlist testing, and password protection.

6. Author

Dharshini R P

Cybersecurity Student

LinkedIn: "Dharshini R P" (https://www.linkedin.com/in/iamdharshini/)

Networkwalks Cybersecurity Internship | Batch B084E


