 **Reading Notes | 7 MAY 2024**

# Class 007

### *Bookmarks:*
[npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)


## **Questions & Answers**
### What is a JSON Web Token (JWT)?
A JSON Web Token (JWT) is a compact, URL-safe means of representing claims to be transferred between two parties.

### When should we use JSON Web Tokens?
We should use JSON Web Tokens when we need to securely transmit information between parties as it can be verified and trusted due to its digital signature.

### Claims are expected in which structural component of a JWT?
Claims are expected in the payload component of a JWT.

### If I get a JWT and I can decode the payload, how can we call that secure?
Even if the payload of a JWT can be decoded, it is still considered secure because the integrity of the token is maintained by the signature, which can only be verified with the correct secret key.

### If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
When sending a JWT, both the sender and the receiver must know the secret key, which is used to create and verify the signature.

### Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
Think of it like sending a sealed envelope through a trusted courier where only the sender and receiver know the unique seal's design, ensuring the contents remain private and unaltered during transit.

### Why use JWT?
JWTs are useful because they are compact and self-contained, making them efficient for scenarios where bandwidth and response time are critical, such as mobile or web applications.

### JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
Imagine it like carrying all you need in one small suitcase instead of several large bags; it's easier to handle and move around quickly, especially when traveling through busy networks.

### What are the three components (the structure) of a JWT?
The structure of a JWT consists of three parts: the header, the payload, and the signature.
