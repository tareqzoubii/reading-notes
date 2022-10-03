**_What is OAuth_**
>OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related
**_Give an example of what using OAuth would look like._**
>The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.
**_How does OAuth work? What are the steps that it takes to authenticate the user?_**
>The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
>The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
>The first site gives this token and secret to the initiating user’s client software.
>The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
>If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
>The user approves (or their software silently approves) a particular transaction type at the first website.
>The user is given an approved access token (notice it’s no longer a request token).
>The user gives the approved access token to the first website.
>The first website gives the access token to the second website as proof of authentication on behalf of the user.
>The second website lets the first website access their site on behalf of the user.
>The user sees a successfully completed transaction occurring.
**_What is OpenID?_**
>OpenID is about authentication: as a commenter on StackOverflow pithily put it: "OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans."


**_What is the difference between authorization and authentication?_**
>Authentication and authorization are two vital information security processes that administrators use to protect systems and information. Authentication verifies the identity of a user or service, and authorization determines their access rights.
**_What is Authorization Code Flow?_**
>which exchanges an Authorization Code for a token. Your app must be server-side because during this exchange, you must also pass along your application's Client Secret, which must always be kept secure, and you will have to store it in your client.
**_What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?_**
>![IMAGE](https://images.ctfassets.net/cdy7uua7fh8z/3pstjSYx3YNSiJQnwKZvm5/33c941faf2e0c434a9ab1f0f3a06e13a/auth-sequence-auth-code-pkce.png)
**_What is Implicit Flow with Form Post_**
>Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. 
**_What is Client Credentials Flow?_**
>such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user.
**_What is Device Authorization Flow?_**
>The Device Authorization Flow contains two different paths; one occurs on the device requesting authorization and the other occurs in a browser. The browser flow path, wherein a device code is bound to the session in the browser, occurs in parallel to part of the device flow path.
**_What is Resource Owner Password Flow?_**
>requests that users provide credentials (username and password), typically using an interactive form. Because credentials are sent to the backend and can be stored for future use before being exchanged for an Access Token, it is imperative that the application is absolutely trusted with this information.