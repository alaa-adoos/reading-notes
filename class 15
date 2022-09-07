# Authentication


## What is OAuth?

### OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

## Give an example of what using OAuth would look like.
### The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon


## How does OAuth work? What are the steps that it takes to authenticate the user?
# OAuth only works using HTTPS

- ### he first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity

- ### The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

- ### The first site gives this token and secret to the initiating user’s client software.

- ### The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).

- ### If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

- ### The user approves (or their software silently approves) a particular transaction type at the first website.

- ### The user is given an approved access token (notice it’s no longer a request token).

- ### The user gives the approved access token to the first website.

- ### The first website gives the access token to the second website as proof of authentication on behalf of the user.

- ### The second website lets the first website access their site on behalf of the user.

- ### The user sees a successfully completed transaction occurring.

- ###  OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).


## What is OpenID? 
### OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans.



## What is the difference between authorization and authentication?
### Authentication verifies the identity of a user or service
### authorization determines their access rights


## What is Authorization Code Flow?

### Used to obtain an access token to authorize API requests



## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
### an OpenId Connect flow specifically designed to authenticate native or mobile application users

## What is Implicit Flow with Form Post?
###  uses OIDC to implement web sign-in

## What is Client Credentials Flow?
### permissions are granted directly to the application itself by an administrator

## What is Device Authorization Flow?
### extension that enables devices with no browser or limited input

## What is Resource Owner Password Flow?
### allows exchanging the username and password of a user for an access token and, optionally, a refresh token