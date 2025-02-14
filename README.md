# ins_task1

# Comparative Analysis of Classical Encryption Techniques

This project explores a comparative analysis of three classical encryption methods: the **Playfair Cipher**, the **Hill Cipher**, and the **Vigenère Cipher**. It examines their encryption mechanisms, computational complexities, as well as their strengths and weaknesses. Additionally, the project investigates cryptanalysis techniques for each cipher and discusses their inherent vulnerabilities. Finally, a proposed hybrid cipher design is presented to overcome the limitations of these classical methods.

## Table of Contents
1. [Introduction](#introduction)
2. [Encryption Techniques](#encryption-techniques)
    - [Playfair Cipher](#playfair-cipher)
    - [Hill Cipher](#hill-cipher)
    - [Vigenère Cipher](#vigenère-cipher)
3. [Cryptanalysis](#cryptanalysis)
    - [Playfair Cipher](#cryptanalysis-of-playfair-cipher)
    - [Hill Cipher](#cryptanalysis-of-hill-cipher)
    - [Vigenère Cipher](#cryptanalysis-of-vigenère-cipher)
4. [Hybrid Cipher Design](#hybrid-cipher-design)
5. [How to Use](#how-to-use)
6. [License](#license)

---

## Introduction
Classical encryption techniques form the cornerstone of cryptography. Although they are no longer secure by contemporary standards, they provide essential insights into the development of cryptographic methods. This project offers a detailed exploration of the Playfair, Hill, and Vigenère Ciphers, shedding light on their strengths, limitations, and vulnerabilities.

---

## Encryption Techniques

### Playfair Cipher
- **Mechanism:** A digraphic substitution cipher utilizing a 5x5 matrix built on a keyword.
- **Strengths:** More resistant to frequency analysis than monoalphabetic ciphers.
- **Weaknesses:** Restricted key space and vulnerable to known plaintext attacks.

### Hill Cipher
- **Mechanism:** A polygraphic substitution cipher that leverages linear algebra and matrix multiplication.
- **Strengths:** Encrypts multiple characters simultaneously.
- **Weaknesses:** Vulnerable to known plaintext attacks and requires invertible key matrices.

### Vigenère Cipher
- **Mechanism:** A polyalphabetic substitution cipher that employs a repeating keyword.
- **Strengths:** Significantly reduces the effectiveness of frequency analysis.
- **Weaknesses:** Vulnerable to Kasiski examination and frequency analysis if the keyword is short.

---

## Cryptanalysis

### Cryptanalysis of Playfair Cipher
- Techniques: Digraph frequency analysis, known plaintext attacks.
- Mathematical Weakness: The key space is limited (~2^84 possible keys).

### Cryptanalysis of Hill Cipher
- Techniques: Key matrix reconstruction through known plaintext attacks.
- Mathematical Weakness: Smaller key matrices are more prone to cryptanalysis.

### Cryptanalysis of Vigenère Cipher
- Techniques: Kasiski examination, frequency analysis of ciphertext segments.
- Mathematical Weakness: Repeated keywords can create detectable statistical patterns.

---

## Hybrid Cipher Design
The hybrid cipher combines elements from multiple classical encryption techniques to enhance security while maintaining simplicity. By layering different encryption methods, it aims to mitigate the individual vulnerabilities inherent in each classical cipher.

---

## How to Use:
Clone the repository:
```bash
git clone https://github.com/kshithijshetty/ins_task1....
```

