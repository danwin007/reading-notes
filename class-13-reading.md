
1. When is Basic Authorization used vs. Bearer Authorization?
- Basic auth is auth that uses a username and a secret. Bearer auth is auth that uses a token.
2. What does the JSON Web Token package do?
- It is a standardized way of generating tokens. It securely transmits info between systems as a JSON object. This info is verified and trusted because it gets a digital signature. That signing process uses a secret key that only the server knows.
3. What considerations should we make when creating and storing a SECRET?
- We should ensure that only the server knows the answer? And that we don't put sensitive info into it?
