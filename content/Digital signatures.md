---
title: "Digital signatures" 
---
> [!SUMMARY]+
> A digital signature is a unique piece of data that is used to verify the identity of a person

This is done through the generation of a private(secret) key and a public key pair. Both the pk and sk are a string of bits. The secret key should only be known by the person who generated it. 

The digital signature is a function with two parameters: a message, and the secret key.
$$
\text{Sign(Message, sk)} = \text{ Signature}
$$
The signature is verified with another function with three parameters:
$$
\text{Verify(Message, Signature, pk)} = \text{ True or False}
$$
As the signature is 256 bits, attempting to brute force a verification can be considered impossible and that whoever can verify a transaction as "True" is assumed to have the secret key paired to the public key

---
- Index:: [[_Cryptocurrency]]
- Related:: [[Bitcoin]]
---