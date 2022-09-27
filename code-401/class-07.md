Reading: Bearer Authorization
=============================

Reading
-------

[Intro to JWT](https://jwt.io/introduction/)

1. What is a JSON Web Token (JWT)?

    * open standard for securely transmitting information as a JSON object

2. When should we use JSON Web Tokens?

    * authorization and info exchange,

3. Claims are expected in which structural component of a JWT?

    * payload

[Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

1. If I get a JWT and I can decode the payload, how can we call that secure?

    * the token is sent with a secret that both(all) parties need to know to be able to decode the message.

2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

    * the secret

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

    * the content and secret are hashed before sending, which scrambles the data in a computer readable code

Videos
------

[JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

1. Why use JWT?

    * it is compact and self-contained

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

    * it is lightweight (quick and easy to transmit) and exists on it's own, so there are less points of failures, i.e opportunities for bugs or intrusion

3. What are the three components (the structure) of a JWT signature?

    * hash, content, secret

Bookmark and Review
-------------------

* [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)
