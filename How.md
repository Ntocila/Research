## Introduction

While there is no such thing as 100% secure, you can take specific measures to mitigate against a wide range of attacks and secure your webapp as much as possible.
Below I you will find some of the most important steps and conecpts that any developer needs to follow for a secure web application.

## Important Principles For A Secure Web Appliation
1. Use SSL only
2. Use Strict Transport Security
3. Enforce a Content Security Policy
4. Enable HTTP security headers
5. Offer Multi Factor Authentication
6. Encrypt All Data
7. Use Authorized APIs Only
8. Use High-Level Authentication

## Identity Server 4
After, researching about different ways of securing a web application and API I came across the Identity Server 4.
IdentityServer is an OpenID Connect provider - it implements the OpenID Connect and OAuth 2.0 protocols.
Different literature uses different terms for the same role - you probably also find security token service, identity provider, authorization server, IP-STS and more.
But they are in a nutshell all the same: a piece of software that issues security tokens to clients.
IdentityServer has a number of jobs and features - including:

* protect your resources
* authenticate users using a local account store or via an external identity provider
* provide session management and single sign-on
* manage and authenticate clients
* issue identity and access tokens to clients
* validate tokens

<br/>

## Personal Opinion

For my personal project I am using Identity Server 4 to secure my web API. The reason I chose Identity Server 4 is because it has the complete package to secure your web application. Basically, IdentityServer is an authentication server that implements OpenID Connect (OIDC) and OAuth 2.0 standards for ASP.NET Core. It's designed to provide a common way to authenticate requests to all of your applications, whether they're web, native, mobile, or API endpoints. In addition, other reasons that made me choose IdentityServer are:
1. Open Source - Free Version
2. Authentication of the users and/or clients.
3. Single Sign-On.

<br/>
<br/>

## Conclusion
To implement IdentityServer4 on your own project you can follow the link below <br/>
https://identityserver4.readthedocs.io/en/latest/quickstarts/0_overview.html <br/>
The link includes all the necessary steps to help you achieve a succesfull and secure web application with IdentityServer4.
