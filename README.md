LIGO SciTokens Public Keys
==========================

This repo provides [SciTokens](https://scitokens.org/) public key verification for the https://scitokens.org/ligo issuer.

https://scitokens.org/ligo is a GitHub Site using Cloudflare. We publish files to the GitHub Site with a .json extension to get the required "content-type: application/json" then use a [Cloudflare rewrite rule](https://blog.cloudflare.com/introducing-transform-rules-with-url-rewriting-at-the-edge/) to publish at the expected locations:
* https://scitokens.org/ligo/.well-known/openid-configuration
* https://scitokens.org/ligo/oauth2/certs
