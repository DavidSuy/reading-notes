# Reading: Bearer Authorization

## [Intro to JWT](https://jwt.io/introduction/)

1. What is a JSON Web Token (JWT)?

   JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

2. When should we use JSON Web Tokens?

   The two most common uses for JWT is for authorization and information exchange.

3. Claims are expected in which structural component of a JWT?

   The second part of the token is the payload, which contains the claims. Claims are statements about an entity (typically, the user) and additional data. There are three types of claims: registered, public, and private claims.

## [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

1. If I get a JWT and I can decode the payload, how can we call that secure?

   JWTs can be either signed, encrypted or both. If a token is signed, but not encrypted, everyone can read its contents, but when you don't know the private key, you can't change it. Otherwise, the receiver will notice that the signature won't match anymore.

2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

   All Auth0-issued JWTs have JSON Web Signatures (JWSs), meaning they are signed rather than encrypted. A JWS represents content secured with digital signatures or Message Authentication Codes (MACs) using JSON-based data structures.

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

   Let's suppose, I send another person the message {"id":1} and sign it with Hash(content + secret). (+ is just concatenation here). I use the SHA256 Hash function, and the signature I get is: 330e7b0775561c6e95797d4dd306a150046e239986f0a1373230fda0235bda8c. Now it's your turn: play the role of Mallory and try to sign the message {"id":2}. You can't because you don't know which secret I used. If I suppose that the recipient knows the secret, he CAN calculate the signature of any message and check if it's correct.

## Videos

[JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

1. Why use JWT?

   JWT can be used as an access token to prevent unwanted access to a protected resource. They're often used as Bearer tokens, which the API will decode and validate before sending a response.

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

   Benefits. There are benefits to using JWTs when compared to simple web tokens (SWTs) and Security Assertion Markup Language (SAML) tokens. More compact: JSON is less verbose than XML, so when it is encoded, a JWT is smaller than a SAML token. This makes JWT a good choice to be passed in HTML and HTTP environments.

3. What are the three components (the structure) of a JWT signature?

   A JWS (the most common type of JWT) contains three parts separated by a dot ( . ). The first two parts (the "header" and "payload") are Base64-URL encoded JSON, and the third is a cryptographic signature.

## Bookmark and Review

- [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)
