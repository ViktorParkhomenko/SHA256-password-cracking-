# SHA256 password cracking using Python

Project Overview

This project features a Python script designed to crack SHA-256 hashed passwords through a brute-force dictionary attack. The script accepts a SHA-256 hash as input, then iterates through the rockyou.txt wordlist, hashes each word with SHA-256, and compares the result to the provided hash. The objective is to recover the original password that corresponds to the given hash.

By automating the cracking process, this project demonstrates how password hashes can be attacked using brute-force methods and highlights the critical need for strong, non-dictionary-based passwords in cybersecurity. It offers valuable insights into hash functions, wordlist-based attacks, and how to efficiently handle large datasets during brute-force operations.
