# Encryption

Encryption is the epitome of cryptography. The goal for encryption is to communicate in secrecy so that only the person who knows how to read it is able to read it.

## Shannon Cipher

The Shannon Cipher is essentially a framework for encryption and decryption

Where :

k = key

m = plaintext message

c = ciphertext message

and E is the encryption function of k and m

and D is the decryption function of k and c

```text
c = E(k,m)
m = D(k,c)
```

**Suppose:**

Alice and Bob want to send a message to each other.

They both decide on a **Key** that only they both know. 

Then Alice **Encrypts** her message with the **Key.**

Then she sends her message to Bob. Assuming that the message was the same message that Alice sent and it was not tampered in transit then Bob can use the shared **Key** and **Decrypt** the message.



### One-Time Pad

A **one-time pad** is a Shannon cipher E = \(E,D\), where the **Keys, Messages**, **and Ciphertext** are bit strings of the **Same Length.**

## Types of Ciphers

### Substitution Cipher



\*\*\*\*

\*\*\*\*





