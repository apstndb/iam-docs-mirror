---
name: documents/docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/Jwks
uri: https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/Jwks
title: Jwks
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/Jwks#SCHEMA_REPRESENTATION)
- [Jwk](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/Jwks#Jwk)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/Jwks#Jwk.SCHEMA_REPRESENTATION)

Response message for [`well-known.getJwks.json`](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common.well-known/getJwks.json#google.cloud.identity.oauth.v1.CloudOAuthService.GetJwks) .

**JSON representation**

```
{
  "keys": [
    {
      object (Jwk)
    }
  ]
}
```

| Fields   |                                                                                                                                                                                                                               |
|----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `keys[]` | `object ( `[`Jwk`](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/Jwks#Jwk)` )` The list of JSON Web Keys (JWKs) that can be used to verify the signature of the ID Token issued by the OpenID Provider. |

## Jwk

A JSON Web Key (JWK) that represents a public cryptographic key.

**JSON representation**

```
{
  "kid": string,
  "kty": string,
  "alg": string,
  "use": string,
  "n": string,
  "e": string,
  "x": string,
  "y": string,
  "crv": string
}
```

| Fields |                                                                                                                                                 |
|--------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| `kid`  | `string` The `kid` (key ID) member is used to match a specific key.                                                                             |
| `kty`  | `string` The `kty` (key type) member identifies the cryptographic algorithm family used with the key, such as `RSA` or `EC` .                   |
| `alg`  | `string` The `alg` (algorithm) member identifies the algorithm intended for use with the key, for example, `RS256` .                            |
| `use`  | `string` The `use` (public key use) member identifies the intended use of the public key. Example values: `sig` and `enc` .                     |
| `n`    | `string` The `n` (modulus) member contains the modulus value for the `RSA` public key. It is represented as a `Base64urlUInt` -encoded value.   |
| `e`    | `string` The `e` (exponent) member contains the exponent value for the `RSA` public key. It is represented as a `Base64urlUInt` -encoded value. |
| `x`    | `string` The `x` (x-coordinate) member contains the x-coordinate for the `EC` elliptic curve point.                                             |
| `y`    | `string` The `y` (y-coordinate) member contains the y-coordinate for the `EC` elliptic curve point.                                             |
| `crv`  | `string` The `crv` (curve) member identifies the cryptographic curve used with the `EC` key.                                                    |
