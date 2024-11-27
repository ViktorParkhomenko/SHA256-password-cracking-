# SHA256 password cracking using Python

Project Overview

This project features a Python script designed to crack SHA-256 hashed passwords through a brute-force dictionary attack. The script accepts a SHA-256 hash as input, then iterates through the rockyou.txt wordlist, hashes each word with SHA-256, and compares the result to the provided hash. The objective is to recover the original password that corresponds to the given hash.

By automating the cracking process, this project demonstrates how password hashes can be attacked using brute-force methods and highlights the critical need for strong, non-dictionary-based passwords in cybersecurity. It offers valuable insights into hash functions, wordlist-based attacks, and how to efficiently handle large datasets during brute-force operations.

![Screenshot_2024-11-27_15-10-56](https://github.com/user-attachments/assets/142b2f25-bc7a-4e53-89ad-a9258b810a16)

Let's generate the SHA-256 hash for the password 'kali' from the rockyou.txt wordlist and then pass that hash into our script

![Screenshot_2024-11-27_15-41-16](https://github.com/user-attachments/assets/34948c79-c428-4015-b746-3a21019259a5)

By executing this script, it will convert the provided hash back into the corresponding password.

![Screenshot_2024-11-27_15-55-21](https://github.com/user-attachments/assets/ca8f5ff2-3b7b-451b-ad73-1a3802808a1e)

Conclusion
This project illustrates how dictionary-based brute-force attacks can be used to break SHA-256 hashes, emphasizing the risks associated with weak or commonly used passwords. By using Python pwntools this project offers a comprehensive guide on how attackers can exploit hashed passwords.

