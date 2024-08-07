# PRODIGY_CS-01
# CAESAR CIPHER ENCRYPTION & DECRYPTIOIN
Caesar cipher is one of the simplest and oldest methods of encryption and decryption. It operates by shifting each letter in the plaintext by a fixed number of positions down or up the alphabet. Here's how it works:

## **Encryption:-**
Choose a Shift: Decide on a number (key) between 1 and 25. This key determines how many positions each letter in the plaintext will be shifted.

Shift Letters: For each letter in the plaintext:

If the letter is a lowercase or uppercase English letter (A-Z or a-z), shift it by the specified number of positions in the alphabet.
Wrap around the alphabet if necessary. For example, shifting 'Z' by 1 gives 'A'.
Create Cipher Text: Replace each letter in the plaintext with the shifted letter to form the ciphertext.

## **Decryption:-**
Decryption with Caesar cipher involves reversing the encryption process:

Know the Shift:- You need to know the exact key (number of positions shifted) used for encryption.

Shift Back:- For each letter in the ciphertext:

Shift it backwards by the same number of positions used in encryption.
Again, wrap around the alphabet as needed.
Retrieve Plain Text: Replace each letter in the ciphertext with the decrypted letter to retrieve the original plaintext.

## **Example:**
Let's say we want to encrypt the plaintext "HELLO" with a key of 3:

H -> K 

E -> H

L -> O

L -> O

O -> R

So, "HELLO" encrypts to "KHOOR" using a Caesar cipher with a key of 3.

## **Security:**
Caesar cipher is very weak by modern standards because there are only 25 possible keys (since a shift of 0 or 26 would result in the original text). It's vulnerable to frequency analysis and brute-force attacks. Therefore, it's mostly used for educational purposes or as part of more complex ciphers or algorithms.
