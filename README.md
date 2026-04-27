# CNS-ALA-2
NAME:DIYA VORA 
ENROLLMENT:240905091019
SUBJECT: Cryptography and Network Security-BETIT16326 (ALA-2)

Cryptographic Hash Functions & Avalanche Effect

This program demonstrates how cryptographic hash functions work and shows an important property called the avalanche effect.

 What is a Hash Function?

A hash function is a mathematical algorithm that converts input data (message) into a fixed-length string called a hash value (digest).

Common hash algorithms used in your program:

SHA-1
SHA-256
SHA-512
✨ Properties of Cryptographic Hash Functions
Deterministic
Same input → same hash every time
Fixed Length Output
Output size is constant (e.g., SHA-256 → 256 bits)
Fast Computation
Hashes are generated quickly
Pre-image Resistance
Cannot easily find original input from hash
Collision Resistance
Very hard to find two inputs with same hash
⚙️ Working of Your Program
1.  Input Messages
User enters:
Original message
Slightly modified message
2.  Hash Generation
sha1 = hashlib.sha1(message.encode()).hexdigest()
sha256 = hashlib.sha256(message.encode()).hexdigest()
sha512 = hashlib.sha512(message.encode()).hexdigest()
The program generates hashes using three algorithms
Each produces a unique fingerprint of the message
3.  Comparison of Hashes
Hashes of both messages are displayed
Even if messages differ slightly → hashes look completely different
 Avalanche Effect

The key concept demonstrated is the avalanche effect:

 A small change in input (even one character) causes a drastic change in output hash

Example:

"Hello" → completely different hash
"hello" → completely different hash

 This ensures:

High security
Strong data integrity
 Important Note
SHA-1 is now considered insecure due to vulnerabilities
Modern systems prefer:
SHA-256
SHA-512
 Applications of Hashing
 Password storage
 File integrity verification
 Digital signatures
 Blockchain technology
✅ Conclusion
The program shows how hashing works
Demonstrates the avalanche effect clearly
Highlights why hashing is important for security and data protection <img width="812" height="569" alt="Screenshot 2026-04-09 002610" src="https://github.com/user-attachments/assets/23381263-13a4-45f5-b29e-5b3dbca63da3" />

