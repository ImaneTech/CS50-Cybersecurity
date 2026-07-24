# Assignment 1 - Securing Data

[Back to main README](../README.md)

## Topics Covered

Passwords, Hashing, Dictionary Attacks, Brute-Force Attacks, Rainbow Tables, Salting, One-Way Hash Functions, Cryptographic Hash Functions, Cryptography, Codes, Ciphers, Encryption, Decryption, Keys, Secret-Key Cryptography, Cryptanalysis, Public-Key Cryptography, RSA, Key Exchange, Diffie-Hellman, Digital Signatures, Passkeys, Encryption in Transit, End-to-End Encryption, Deletion, Secure Deletion, Full-Disk Encryption, Encryption at Rest, Ransomware, Quantum Computing.

## Summary

This assignment explores how data is protected both at rest and in transit through hashing and cryptography. It covers one-way hash functions and salting as a defense against rainbow table attacks, and contrasts secret-key (symmetric) cryptography with public-key (asymmetric) cryptography, including RSA and Diffie-Hellman key exchange. It also addresses secure deletion, full-disk encryption, and the emerging threat that quantum computing poses to current cryptographic standards.

## Key Takeaways

- Passwords should never be stored in plaintext; salted cryptographic hashes prevent precomputed rainbow table attacks.
- Symmetric encryption is fast and efficient for bulk data, while asymmetric encryption solves the key distribution problem through public/private key pairs.
- Diffie-Hellman key exchange allows two parties to establish a shared secret over an insecure channel without transmitting the key itself.
- Digital signatures provide integrity and non-repudiation by combining hashing with public-key cryptography.
- Standard file deletion does not erase data; secure deletion and full-disk encryption are required to protect data at rest.

## Status

Project complete.
