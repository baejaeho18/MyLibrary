# Computer Security
Definition : The projection affor to an automated information system in order to attain the applicable objectives of preserving the integrity, availability and confidentiality information system resources  - [An Introduction to Computer Security: The NIST Handbook](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-12r1.pdf)

<img width="172" alt="image" src="https://github.com/baejaeho18/MyLibrary/assets/37645490/0590efe1-53b3-4251-927a-c9b2b4483661">

# Crpytography
## Crpytography Techniques
* Type of encrpytion Operations
  - SubStitution(S-box) : mapping to other symbol
    * Monoaplhabetic Ciphers : one-to-one
      ex) Caesar cipher(additive or shift cipher)
    * Homophonic Substitution Cipher : one-to-many
    * Polygram Substitution Cipher : Block-by-Block replacement
    * Polyalphabetic Substition Cipher
      ex) Autokey - pre-Plain character became a key
  - Transposition(P-box) : reorder the symbols
    * Keyless : Columnar Transposition. Vernam(one-time key) cipher
    * Keyed
    * Combined
  - Others : XOR, Circular shift, Swap, Split and Combine
  - Product : Multi Rounds of substitutions and transpositon
    * Diffusion : ciphertext-plaintext
    * Confusion : ciphertext-key
* Number of Keys used : must be secure even if everything, except the key, is the public (Kerckhoffs's Principle)
  - Symmetric Key : Single-key or secret
  - Asymmetric key : Two-key or public
* Type of Algorithms : define the size of plain text
  - Block
  - Stream


## Symmetric Key Crpytographic Algorithms
* Invertible
  - Feistel Cipher : 
  - Non-Feistel Cipher : only invertivle components
* DES

  - Triple-DES with Two-Keys
* AES
* Algorithm Modes
  - ECB(Electronic Code Book)
  - CBC(Cipher Block Chaining)
  - CFB(Cipher FeedBack)
  - OFB(Output FeedBack)
  - CTR(Counter)
## Asymmetric Key Cryptography Algorithms
* RSA
* Digital Signature
* Hash Functions
  - SHA-512
  - Whirlpool Hash Function
* MAC(Message Authentication Code)


# 
