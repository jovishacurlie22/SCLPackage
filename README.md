# SCLPackage
Cryptographic Techniques Showcase (Menu-Driven Python Program)

This project is a menu-driven Python application that demonstrates the core concepts of four popular cryptographic techniques:

- Caesar Cipher
- Vigenère Cipher
- AES (Advanced Encryption Standard)
- RSA (Rivest–Shamir–Adleman)

It allows users to encrypt and decrypt messages interactively from the command line.

Features:
- Caesar Cipher: Simple substitution cipher with shift value.
- Vigenère Cipher: Polyalphabetic substitution using a keyword.
- AES Encryption: Symmetric encryption with CBC mode.
- RSA Encryption: Public-key encryption using randomly generated primes.

Installation:
Install the required libraries using pip:
    pip install pycryptodome sympy

If you're using Google Colab:
    !pip install pycryptodome sympy

Usage:
1. Run the script: python crypto_menu.py
2. Choose an encryption method.
3. Enter your message and key (if required).
4. View the encrypted and decrypted output.

Notes:
- AES generates a new 128-bit key each time for demonstration.
- RSA uses small key sizes for demo purposes only; use 2048+ bits for secure applications.
- This project is intended for educational purposes.
