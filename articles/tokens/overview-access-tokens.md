---
title: Access Tokens
description: Learn what Access Tokens are and how you can use them with Auth0.
toc: true
topics:
  - tokens
  - access-tokens
contentType:
  - concept
useCase:
  - invoke-api
---
# Access Tokens

An Access Token is a credential that can be used by an application to access an API. Access Tokens can be either an opaque string or a JSON web token. They inform the API that the bearer of the token has been authorized to access the API and perform specific actions specified by the **scope** that has been granted. 

Access Tokens should be used as a **Bearer** credential and transmitted in an HTTP **Authorization** header to the API. 

Depending on how your application needs to use the Access Token, you can do the following:

* [Set the Access Token format](/set-access-token-format) to either an opaque string or a JSON web token.
* [Get Access Tokens](/get-access-tokens) using any OAuth 2.0-compatible library or you can use one of Auth0's libraries that work with Auth0 endpoints.
* [Use Access Tokens](/use-access-tokens) either in server-to-server or customer API interactions.
* [Add Custom Claims](/add-custom-claims) using [Rules](/rules).
* [Set an Access Token's lifetime](/set-access-token-lifetime).