# Diffie-Hellman


**The Diffie-Hellman key exchange (also known as exponential key exchange) is a method for securely exchanging cryptographic keys over an insecure channel. It is a fundamental building block of many secure communication protocols, including SSL/TLS and SSH.<br><br>**

**The Diffie-Hellman key exchange works by allowing two parties (Alice and Bob) to agree on a shared secret key over an insecure channel, without any other party being able to intercept the key or learn anything about it.** The key exchange involves the following steps −<br><br> 


Alice and Bob agree on two large prime numbers, p and g, and a public key exchange algorithm.<br>

Alice chooses a secret integer, a, and computes A = g^a mod p. She sends A to Bob.<br>

Bob chooses a secret integer, b, and computes B = g^b mod p. He sends B to Alice.<br>

Alice computes s = B^a mod p. Bob computes s = A^b mod p.<br>

Alice and Bob now both have shared secret keys, which they can use to establish a secure communication channel.<br>

**The security of the Diffie-Hellman key exchange relies on the fact that it is computationally infeasible for an attacker to determine the shared secret keys from the public values of p, g, A, and B. This allows Alice and Bob to exchange the key securely, even over an insecure channel.  **<br><br>

**Where is Diffie-Hellman Key Exchange Used?**

The Diffie-Hellman key exchange (also known as exponential key exchange) is a widely used and trusted technique for securely exchanging cryptographic keys over an insecure channel. It is used in many different contexts, including −<br>

Secure communication protocols − The Diffie-Hellman key exchange is used in many secure communication protocols, such as SSL/TLS and SSH, to establish a secure channel between two parties. It allows the parties to agree on a shared secret key that can be used to encrypt and decrypt messages exchanged over the channel.<br>

Virtual private networks (VPNs) − The Diffie-Hellman key exchange is often used in VPNs to establish a secure connection between a client and a server. It allows the client and server to agree on a shared secret key that can be used to encrypt and decrypt traffic exchanged over the VPN connection.<br>

Secure file transfer protocols − The Diffie-Hellman key exchange is used in many secure file transfer protocols,such as SFTP and FTPS, to establish a secure channel for transferring files between two parties.It allows the parties to agree on a shared secret key that can be used to encrypt and decrypt the transferred files.<br>

![Public_key_shared_secret svg](https://github.com/bensonjose/Diffie-Hellman-Explained/assets/90842204/19b6ecf6-72a3-4841-ba38-b81fa3d391ee)

