# Readings: Authentication

## [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

1. Explain to a non-technical friend how you would safely hash and store a password.

   General purpose hash functions, designed to calculate a digest of huge amounts of data in as short a time as possible. Hashing is the greatest way for protecting passwords and considered to be pretty safe for ensuring the integrity of data or password.

2. What is Bcrypt?

   Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.

3. Why might you use something like Bcrypt?

   Bcrypt algorithms which can make the brute force attacks slower and minimize the impact.

## [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

1. What is Basic Authentication?

   Basic access authentication is a method for an HTTP user agent to provide a user name and password when making a request.

2. What properties are necessary in the header of a Basic Auth request?

   - Basic Auth
   - Bearer Token
   - API Key
   - Digest Auth
   - OAuth 2.0
   - Hawk Authentication
   - AWS Signature

3. How are `username:password` in Basic Auth encoded?

   It's encoded in Base64

## [OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

1. Define the authentication process to a non-technical recruiter.

   Authentication is the process of verifying that an individual, entity or website is whom it claims to be. Authentication in the context of web applications is commonly performed by submitting a username or ID and one or more items of private information that only a given user should know.

2. How should your error messaging respond (both HTTP and HTML)? Why?

   Incorrectly implemented error messages in the case of authentication functionality can be used for the purposes of user ID and password enumeration. An application should respond (both HTTP and HTML) in a generic manner. The objective is to prevent the creation of a discrepancy factor, allowing an attacker to mount a user enumeration action against the application.

3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

## Bookmark and Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)
