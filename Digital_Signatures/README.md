# Digital signatures

- https://en.wikipedia.org/wiki/Digital_signature
- https://www.youtube.com/watch?v=JR4_RBb8A9Q

A **digital signature** is a mathematical scheme for verifying the authenticity of digital messages or documents (Like the pen and paper signatures)

- only you can sign arbitrary messages (or other words, nobody should be able to forge your signature)
- anybody can verify a signature on messages that you’ve signed

A digital signature scheme typically consists of three algorithms;

1. A *key generation algorithm* that selects a private key uniformly at random from a set of possible private keys. The algorithm outputs the **private key** and a corresponding **public key**.
2. A *signing algorithm* that, given a message and a private key, produces a **signature**.
3. A *signature verifying algorithm* that, given the message, public key and signature, either **accepts** or **rejects** the message's claim to authenticity.

# Suggested reading order
1. DSA signatures -> read online
2. RSA signatures
3. Elliptic curve DSA