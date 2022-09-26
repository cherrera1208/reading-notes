Readings: Authentication
========================

Readings
--------

[Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

1. Explain to a non-technical friend how you would safely hash and store a password.

    * encrypt the password string by using one of the common hashing algorithms (SHA256, SHA512, etc...) and store that value instead of the string.

2. What is Bcrypt?

    * introduces a work factor, i.e security factor, which determines how "expensive" the hash is. THis makes it more difficult to brute force an encryption.

3. Why might you use something like Bcrypt?

    * if you needed better security. Actually, it sounds like bcrypt is generally better overall, but it is slower than Base64.

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

1. What is Basic Authentication?

    * confirming a person's identity with credentials

2. What properties are necessary in the header of a Basic Auth request?

    * id and password

3. How are `username:password` in Basic Auth encoded?

    * Base64  

[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

1. Define the authentication process to a non-technical recruiter.

    * authentication is like checking someone's ID, like a drivers license, passport, or fingerprint, but for specific websites. It's also important to ensure that the agent accessing the site is actually human and not a computer.

2. How should your error messaging respond (both HTTP and HTML)? Why?

    *generically. It shouldn't include any "clues" as to why the password was incorrect, such as _incorrect password_ or _account does not exist_, but instead something like _incorrect credentials_

3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

    * bookmarked ✔️

Bookmark and Review
-------------------

[bcrypt docs](https://www.npmjs.com/package/bcrypt)
