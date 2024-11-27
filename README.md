# SHA256 password cracking using Python

Project Overview

This project features a Python script designed to crack SHA-256 hashed passwords through a brute-force dictionary attack. The script accepts a SHA-256 hash as input, then iterates through the rockyou.txt wordlist, hashes each word with SHA-256, and compares the result to the provided hash. The objective is to recover the original password that corresponds to the given hash.

By automating the cracking process, this project demonstrates how password hashes can be attacked using brute-force methods and highlights the critical need for strong, non-dictionary-based passwords in cybersecurity. It offers valuable insights into hash functions, wordlist-based attacks, and how to efficiently handle large datasets during brute-force operations.

![Screenshot_2024-11-27_15-10-56](https://github.com/user-attachments/assets/142b2f25-bc7a-4e53-89ad-a9258b810a16)

from pwn import * imports all functions and classes from the pwntools library, which is widely used in security research and exploit development for tasks like binary exploitation, networking, and scripting CTF challenges.

import sys imports the sys module, which provides access to system-specific parameters and functions, such as command-line arguments (sys.argv) and system exit functions (sys.exit).

This Python script is designed to brute-force a SHA-256 hashed password using the rockyou.txt wordlist. It checks the number of arguments passed to the script and prints an error message if the input is invalid. The script then reads each password from the wordlist, hashes it using SHA-256, and compares the hash with the target hash provided as a command-line argument. If a match is found, it prints a success message and stops the program, displaying the number of attempts made. If no match is found after trying all passwords, it prints a failure message indicating that the hash could not be cracked.
