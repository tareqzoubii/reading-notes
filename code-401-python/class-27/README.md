# READ 27

## JSON WEB TOKENS

### What are JSON Web Tokens used for?
> JSON Web Token is an open industry standard used to share information between two entities, usually a client (like your app's frontend) and a server (your app's backend). They contain JSON objects which have the information that needs to be shared.

### What do JSON Web Tokens do?
>JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed.

### How to decode a JWT token in Python?
>The library PyJWT has an option to decode a JWT without verification: Without this option, the decode function does not only decode the token but also verifies the signature and you would have to provide the matching key. And that's of course the recommended way.

### What’s The Point of The Refresh Token?
>At first glance the refresh token may look pointless, but in fact it is necessary to make sure the user still have the correct permissions. If your access token have a long expire time, it may take longer to update the information associated with the token. That’s because the authentication check is done by cryptographic means, instead of querying the database and verifying the data. So some information is sort of cached.

>There is also a security aspect, in a sense that the refresh token only travel in the POST data. And the access token is sent via HTTP header, which may be logged along the way. So this also give a short window, should your access token be compromised.