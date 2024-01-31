# Class 18 - Cryptography

## [Encryption, Decryption & Hacking](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security/xcae6f4a7ff015e7d:data-encryption-techniques/a/encryption-decryption-and-code-cracking)

- One of the first encryption techniques was developed by Julius Ceasar and it involved shifting the letters of the alphabet to disguise a message
- As long as the receiver knew the shift count, then they could decrypt the message
- Without knowing the shift count, there are three ways to "crack" the cipher: frequency analysis, known plaintext and bruthforce
- Encryption: scrambling data according to a secret key
- Decryption: recovering original data from scrambled data using a secret key
- Code cracking: uncovering original data without knowing the secret

## [Ceasar Cipher](https://en.wikipedia.org/wiki/Caesar_cipher)

- Also known as a substitution cipher
- In modern practice, ceasar cipher offers no communications security
- Use brute force technique to list out all 25 shifts and their message outcome and select the message that makes the most sense

## [Cryptography Crash Course](https://www.youtube.com/watch?v=jhXCTbFnK8o)

- Cryptography is a form of computer security
- Key exhange is used to let two computers agree on a key without ever sending one
    - This prevents other users from intercepting the secret key for their own use
    - This is conducted through the use of one-way functions

## Additional Resources

[Intro to Cryptography](https://thebestvpn.com/cryptography/)

[How Computers Generate Random Numbers](https://www.howtogeek.com/183051/htg-explains-how-computers-generate-random-numbers/)

### Questions

1. What is the basic principle behind the Caesar Cipher, and how was it used historically?

- A message is encrypted by using a shift, int: n. Each letter in the alphabet is shifted n amount of times and the corresponding letter after the shift is the output resulting in an encrypted message. The receiver can decrypt the message if they are aware of the shift

2. What are the key differences between symmetric and asymmetric encryption? How is asymmetric used in secure communication today?

- Symmetric encryption is when the same key is used on both sides 
    - In computer science, same key is used on client and server
- Asymemetric encryption is when there are two different keys
    - Having the public key allows the clinet to encrypt and the secret key allows the server to decrypt

3. How do computers generate random numbers, and what are the differences between true random number generation (TRNG) and pseudo-random number generation (PRNG)? Discuss their use cases in cryptography.

- Computers uses some sort of measure to base the numbers randomness.
- True random number bases the random number generation on a measure from a physical phenomenon that takes place outside of the computer
- Pseudorandom number uses a seed value and an algorithm to generate random numbers
- In cryptography, true random is useful for one-time keys whereas psuedorandom is useful for keys that require multiple uses

4. What’s the difference between encryption and decryption? Explain with an analogy.

- Encryption disguises content using a secret technique and decryption reverses the encryption.
- Doors with a lock are a form of physical encryption that prevent strangers from entering. Without the physical key to unlock the door (decrypt the lock), then strangers are prevented from entering. 

## Things I want to know more about

- Some of these techniques seem like they only encrypt numbers or only encrypt letters, but is there a way to combine both into a secret key and encrypt both letters and numbers?