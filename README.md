## **Cryptography CTF - Write-up**

Welcome to the **Cryptography CTF**! This challenge will take you through 50 encryption techniques, testing your ability to crack different cipher texts. From classic ciphers to modern encryption methods, this CTF is a great way to test your cryptography knowledge.

Each challenge will provide you with a cipher text, and your goal is to decode it to uncover a unique part of the flag. Once you’ve solved all 50 challenges, you will combine the decoded answers to unlock the final flag.

---

### **Challenges Overview**

#### 1. **Caesar Cipher**
   - **Ciphertext:** `Vkrqj xlmw hfywjv jvsqv`
   - **Shift:** 3
   - **Technique:** Caesar Cipher shifts letters by a fixed amount.
   - **Decoded Answer:** `CTF{ENCRYPT}`

#### 2. **Vigenère Cipher**
   - **Ciphertext:** `Wjvsxv dv qfwz bw vz`
   - **Key:** `CRYPTO`
   - **Technique:** Vigenère Cipher uses a repeating key to shift letters.
   - **Decoded Answer:** `CTF{FAIZAN}`

#### 3. **Base64 Encoding**
   - **Ciphertext:** `U1RKRQ==`
   - **Hint:** Common encoding method.
   - **Technique:** Base64 encodes binary data as ASCII text.
   - **Decoded Answer:** `CTF{HACKER}`

#### 4. **ROT13 Cipher**
   - **Ciphertext:** `Urf n qbt zbag`
   - **Technique:** ROT13 shifts letters by 13 positions.
   - **Decoded Answer:** `CTF{DECRYPT}`

#### 5. **XOR Cipher**
   - **Ciphertext:** `17, 20, 23, 11, 15, 25, 17`
   - **Key:** `5`
   - **Technique:** XOR cipher combines plaintext with the key using the XOR operation.
   - **Decoded Answer:** `CTF{CIPHER}`

#### 6. **MD5 Hash**
   - **Ciphertext:** `098f6bcd4621d373cade4e832627b4f6`
   - **Technique:** MD5 is a hashing algorithm.
   - **Decoded Answer:** `CTF{SECRET}`

#### 7. **SHA-256 Hash**
   - **Ciphertext:** `9c56f8b750ab45a2fa4a3d43bce3f9579e4d2d763ccbc7fba736b26b2a6fdad9`
   - **Technique:** SHA-256 is a strong cryptographic hash function.
   - **Decoded Answer:** `CTF{ENCRYPTED}`

#### 8. **Affine Cipher**
   - **Ciphertext:** `bzb dw mbf yebw`
   - **Key (a,b):** `(3, 7)`
   - **Technique:** Affine Cipher uses a linear transformation.
   - **Decoded Answer:** `CTF{BLOCKCHAIN}`

#### 9. **Substitution Cipher**
   - **Ciphertext:** `ZOH ZL IR FVZ`
   - **Technique:** Each letter is replaced by another letter.
   - **Decoded Answer:** `CTF{DECRYPTION}`

#### 10. **Atbash Cipher**
   - **Ciphertext:** `Bzfgivvhg`
   - **Technique:** Atbash reverses the alphabet.
   - **Decoded Answer:** `CTF{FLAG}`

#### 11. **Playfair Cipher**
   - **Ciphertext:** `Xlmbsh mngeq`
   - **Key:** `CRYPTO`
   - **Technique:** Playfair Cipher encrypts digraphs (pairs of letters).
   - **Decoded Answer:** `CTF{SECURITY}`

#### 12. **Rail Fence Cipher**
   - **Ciphertext:** `ceT Fr Aayg`
   - **Key:** 3
   - **Technique:** The text is written in a zigzag pattern and then read off in rows.
   - **Decoded Answer:** `CTF{NETWORK}`

#### 13. **Baconian Cipher**
   - **Ciphertext:** `ab aaa abba babb aab`
   - **Technique:** Baconian Cipher maps letters to binary strings.
   - **Decoded Answer:** `CTF{EXAMPLE}`

#### 14. **Morse Code**
   - **Ciphertext:** `-.-. - ..-. -.-. .-.-.-`
   - **Technique:** Morse code uses dots and dashes for letters.
   - **Decoded Answer:** `CTF{ENCODE}`

#### 15. **Beaufort Cipher**
   - **Ciphertext:** `Wxyytk wmjfv`
   - **Key:** `KEY`
   - **Technique:** Beaufort cipher is a variant of the Vigenère cipher.
   - **Decoded Answer:** `CTF{PASSWORD}`

#### 16. **Transposition Cipher**
   - **Ciphertext:** `ltec fdoet`
   - **Technique:** Letters are rearranged according to a key.
   - **Decoded Answer:** `CTF{HACKING}`

#### 17. **Cesar Shift (Negative)**
   - **Ciphertext:** `Wkhuh qvwduh`
   - **Shift:** -3
   - **Technique:** A variation of Caesar cipher with a negative shift.
   - **Decoded Answer:** `CTF{ATTACK}`

#### 18. **Triple DES**
   - **Ciphertext:** `d2d2d2d4`
   - **Technique:** Triple DES encrypts the data three times for added security.
   - **Decoded Answer:** `CTF{TRIPLE}`

#### 19. **RSA Encryption**
   - **Ciphertext:** `l6g74ek8nmn25`
   - **Technique:** RSA uses large prime numbers for encryption.
   - **Decoded Answer:** `CTF{KEYPAIR}`

#### 20. **ElGamal Encryption**
   - **Ciphertext:** `G8y9i61mJw9`
   - **Technique:** ElGamal encryption is based on modular arithmetic.
   - **Decoded Answer:** `CTF{PUBLIC}`

#### 21. **One-Time Pad**
   - **Ciphertext:** `Jfr4h e55f`
   - **Key:** Random, one-time use
   - **Technique:** One-time pad uses a random key for each encryption.
   - **Decoded Answer:** `CTF{SECRETMESSAGE}`

#### 22. **HMAC (Hash-based Message Authentication Code)**
   - **Ciphertext:** `d41d8cd98f00b204e9800998ecf8427e`
   - **Technique:** HMAC uses hashing with a secret key.
   - **Decoded Answer:** `CTF{AUTH}`

#### 23. **Diffie-Hellman Key Exchange**
   - **Ciphertext:** `y27f5gh20`
   - **Technique:** Diffie-Hellman allows two parties to agree on a secret key.
   - **Decoded Answer:** `CTF{EXCHANGE}`

#### 24. **Homophonic Substitution Cipher**
   - **Ciphertext:** `t9 f1g d3d3`
   - **Technique:** Multiple substitutes for the same letter.
   - **Decoded Answer:** `CTF{SECURITYKEY}`

#### 25. **Hill Cipher**
   - **Ciphertext:** `GDH`
   - **Key:** Matrix for encryption
   - **Technique:** Hill cipher uses matrix multiplication.
   - **Decoded Answer:** `CTF{MODULAR}`

#### 26. **Gronsfeld Cipher**
   - **Ciphertext:** `bvv cx`
   - **Key:** `1423`
   - **Technique:** Gronsfeld cipher is a variant of Vigenère with digits.
   - **Decoded Answer:** `CTF{ENCRYPTION}`

#### 27. **Playfair with Digraphs**
   - **Ciphertext:** `MPVGK`
   - **Key:** `SIMPLEKEY`
   - **Technique:** Encrypts text in pairs of letters.
   - **Decoded Answer:** `CTF{PAIR}`

#### 28. **Columnar Transposition Cipher**
   - **Ciphertext:** `SIRCTFAD`
   - **Key:** `3`
   - **Technique:** Letters are written in columns.
   - **Decoded Answer:** `CTF{TRANSPOSE}`

#### 29. **Columnar Transposition (2)**
   - **Ciphertext:** `c0t Hrc fd!`
   - **Technique:** Transposition cipher uses columns to scramble letters.
   - **Decoded Answer:** `CTF{SOLVED}`

#### 30. **Caesar Shift (Variable)**
   - **Ciphertext:** `D5`  
   - **Technique:** Shift length varies.
   - **Decoded Answer:** `CTF{VARIABLE}`

#### 31. **Knapsack Problem Encryption**
   - **Ciphertext:** `45,89,12`
   - **Technique:** A computational problem used for encryption.
   - **Decoded Answer:** `CTF{PROBLEM}`

#### 32. **RSA Key Pair Generation**
   - **Ciphertext:** `mf3f40r`
   - **

Technique:** Public key encryption based on prime numbers.
   - **Decoded Answer:** `CTF{KEYGEN}`

#### 33. **Fermat's Little Theorem**
   - **Ciphertext:** `LDCi`
   - **Technique:** Mathematical theorem for generating keys.
   - **Decoded Answer:** `CTF{MATHEMATICS}`

#### 34. **Affine with Different Constants**
   - **Ciphertext:** `xxge`
   - **Key:** `(3, 6)`
   - **Decoded Answer:** `CTF{MOD}`

#### 35. **One-Time Pad XOR Encryption**
   - **Ciphertext:** `r2p5t12`
   - **Technique:** One-time pad encryption method with XOR.
   - **Decoded Answer:** `CTF{UNIQUE}`

#### 36. **Advanced Encryption Standard (AES)**
   - **Ciphertext:** `aad457ddad45`
   - **Technique:** AES for encryption and decryption of data.
   - **Decoded Answer:** `CTF{BLOCKCIPHER}`

#### 37. **Base32 Encoding**
   - **Ciphertext:** `UDEBZXI2XQ==`
   - **Technique:** Base32 encoding.
   - **Decoded Answer:** `CTF{ENCODED}`

#### 38. **Polybius Square**
   - **Ciphertext:** `14 23 12 34`
   - **Technique:** Polybius square is a form of substitution cipher.
   - **Decoded Answer:** `CTF{GRID}`

#### 39. **Double Transposition Cipher**
   - **Ciphertext:** `CTF T HEE AEGN`
   - **Technique:** Two-step transposition cipher.
   - **Decoded Answer:** `CTF{DECODED}`

#### 40. **ElGamal Signature**
   - **Ciphertext:** `x5b2wfd2`
   - **Technique:** ElGamal signature provides message authentication.
   - **Decoded Answer:** `CTF{SIGNATURE}`

#### 41. **Multiplicative Cipher**
   - **Ciphertext:** `75 53`
   - **Technique:** Multiplicative cipher uses modulo multiplication.
   - **Decoded Answer:** `CTF{MUL}`

#### 42. **Fibonacci Cipher**
   - **Ciphertext:** `6 4 10 6 8`
   - **Decoded Answer:** `CTF{FIBO}`

#### 43. **Trithemius Cipher**
   - **Ciphertext:** `jkk eal`
   - **Technique:** Caesar cipher with varying shifts.
   - **Decoded Answer:** `CTF{CYPHER}`

#### 44. **Cryptogram**
   - **Ciphertext:** `qlzh qot`
   - **Technique:** Simple cipher with constant shifts.
   - **Decoded Answer:** `CTF{CODE}`

#### 45. **Sieve of Eratosthenes Cipher**
   - **Ciphertext:** `3154 1542`
   - **Technique:** Encrypting numbers with prime sieve.
   - **Decoded Answer:** `CTF{PRIME}`

#### 46. **Permutation Cipher**
   - **Ciphertext:** `dfga btrw`
   - **Technique:** Reordering letters in a systematic way.
   - **Decoded Answer:** `CTF{SORT}`

#### 47. **Homophonic Cipher**
   - **Ciphertext:** `2 7 6 7`
   - **Technique:** Multiple cipher letters for each character.
   - **Decoded Answer:** `CTF{HOMOPHONE}`

#### 48. **Bifid Cipher**
   - **Ciphertext:** `c5f q2z`
   - **Technique:** Combining polybius and transposition.
   - **Decoded Answer:** `CTF{BIFID}`

#### 49. **Permutation-based Cipher**
   - **Ciphertext:** `f3 e7 d9 7b`
   - **Technique:** Rearranging ciphertext.
   - **Decoded Answer:** `CTF{PERM}`

#### 50. **Chin Cipher**
   - **Ciphertext:** `kcb xslg`
   - **Technique:** Encrypting letters using an integer shift.
   - **Decoded Answer:** `CTF{SHIFT}`

---
## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Faizan-Khanx/THM-CryptoGraphy-CTF/blob/main/LICENSE.md)) file for details.

---

## Contact

For any questions or feedback, please contact [E-Mail Me](mailto:fk776794@gmail.com?subject=Feedback%20on%20Faizan%20Net&body=Hello%20Faizan,%0A%0AI%20have%20some%20feedback%20to%20share%20about%20your%20Faizan%20Net%20tool.%0A%0A%2D%20Issue%2FComplaint%3A%20[Please%20describe%20the%20issue%20or%20complaint]%0A%2D%20Suggestions%2FChanges%3A%20[Please%20provide%20your%20suggestions%20or%20changes]%0A%0AThank%20you!%0A%0ARegards,%0A[Your%20Name])

---

<!-- display the social media buttons in your README -->

[![instagram](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/Instagram.png (Instagram))][2]
[![twitter](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/Twitter.png (Twitter))][3]
[![linkedin](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/LinkedIn.png (LinkedIn))][4]
[![github](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/Github.png (Github))][5]
---

<!-- To Link your profile to the media buttons -->

[2]: https://www.instagram.com/EthicalFaizan
[3]: https://www.twitter.com/EthicalFaizan
[4]: https://www.linkedin.com/in/EthicalFaizan
[5]: https://www.github.com/faizan-khanx

---

## GITHUB STATS

![Faizan's GitHub stats](https://github-readme-stats.vercel.app/api?username=faizan-khanx&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage&theme=dark#gh-dark-mode-only)
