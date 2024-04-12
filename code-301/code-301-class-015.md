# **Reading Notes | 12 APR 2024**

# Class 015

## **Bookmarks**  

[Auth0 for single page apps](https://auth0.com/docs/libraries/auth0-react)  

## **Questions & Answers**  

### What is OAuth?

OAuth is an open standard for access delegation, commonly used as a way for Internet users to grant websites or applications access to their information on other websites but without giving them the passwords.

### Give an example of what using OAuth would look like

An example of using OAuth would be when a user logs into a service (like a music streaming app) using their Google account credentials, thereby authorizing the app to access certain information from their Google profile.

### How does OAuth work? What are the steps that it takes to authenticate the user?

OAuth works by providing a secure delegated access to server resources on behalf of a resource owner. It involves several steps:

1. Requesting authorization from the resource owner.
2. The client receiving an authorization grant.
3. Exchanging the authorization grant for an access token.
4. Using the access token to access the protected resources.

### What is OpenID?

OpenID is an authentication layer on top of OAuth, used for verifying the user's identity through the authentication performed by the authorization server, as opposed to just delegating access to resources.

### What is the difference between authorization and authentication?

Authentication is the process of verifying who a user is, while authorization is the process of verifying what specific applications, files, and data a user has access to.

### What is Authorization Code Flow?

Authorization Code Flow is an OAuth 2.0 flow that exchanges an authorization code for an access token. This code is obtained by redirecting a resource owner to an authorization server, then redirecting back to the client with the authorization code.

### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

Authorization Code Flow with PKCE is an enhancement of the standard Authorization Code flow to prevent certain attacks and is recommended for clients that can't hold client secrets securely, especially mobile and desktop applications.

### What is Implicit Flow with Form Post?

Implicit Flow with Form Post is a simplified OAuth flow previously recommended for clients without a secret, such as JavaScript or mobile apps, where the access token is returned immediately without an extra authorization code exchange step.

### What is Client Credentials Flow?

Client Credentials Flow is an OAuth flow where the client application can directly request an access token to access its own resources rather than acting on behalf of a user.

### What is Device Authorization Flow?

Device Authorization Flow is an OAuth 2.0 flow that allows devices without browsers or limited input capability to authorize user accounts by displaying a verification code to enter on a secondary device.

### What is Resource Owner Password Flow?

Resource Owner Password Flow is an OAuth grant that allows credentials to be used directly by an application to authenticate the user, considered less secure and not recommended for new applications
