## Authentication

**What is OAuth**

1. What is OAuth?

  - is an authentication protocol that allows you to approve one application
    interacting with another on your behalf without giving away your password.


2. Give an example of what using OAuth would look like: is one website saying 
   “hey, do you want to log into our website with other website's login?” In this
   scenario, the only thing the first website – let's refer to that website as the 
   consumer – wants to know is that the user is the same user on both websites and 
   has logged in.


3. How does OAuth work? What are the steps that it takes to authenticate the user?

  - OAuth doesn't share password data but instead uses authorization tokens to prove
   an identity between consumers and service providers. OAuth is an authentication 
   protocol that allows you to approve one application interacting with another on 
   4your behalf without giving away your password.


4. What is OpenID?

  - It allows you to use an existing account to sign in to multiple websites, without 
    needing to create new passwords.



**Authorization and Authentication flows**


1. What is the difference between authorization and authentication?

  - Authentication and authorization might sound similar, but they are distinct security
    processes in the world of identity and access management (IAM). Authentication confirms
    that users are who they say they are. Authorization gives those users permission to 
    access a resource.

2. What is Authorization Code Flow?

  - is described in section 4.1 of the OAuth 2.0 specification. It's used to perform 
    authentication and authorization in the majority of app types, including single 
    page apps, web apps, and natively installed apps.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

  - is an OpenId Connect flow specifically designed to authenticate native or mobile 
    application users. This flow is considered best practice when using Single Page Apps 
    (SPA) or Mobile Apps. PKCE, pronounced “pixy” is an acronym for Proof Key for Code Exchange.


4. What is Implicit Flow with Form Post?

  - Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar
    to the way SAML and WS-Federation operates. The web app requests and obtains tokens through 
    the front channel, without the need for secrets or extra backend calls.


5. What is Client Credentials Flow?

  - The Client Credentials flow is a server to server flow. 


6. What is Device Authorization Flow?

  -  is an OAuth 2.0 extension that enables devices with no browser or limited input capability
     to obtain an access token. This is commonly seen on Apple TV apps, or devices like hardware
     encoders that can stream video to a YouTube channel.


7. What is Resource Owner Password Flow?

  -  Credentials flow allows exchanging the username and password of a user for an access token 
     and, optionally, a refresh token.