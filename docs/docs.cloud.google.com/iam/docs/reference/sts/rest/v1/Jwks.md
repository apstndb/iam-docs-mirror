---
name: documents/docs.cloud.google.com/iam/docs/reference/sts/rest/v1/Jwks
uri: https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/Jwks
title: Jwks
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/Jwks#SCHEMA_REPRESENTATION)
- [Jwk](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/Jwks#Jwk)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/Jwks#Jwk.SCHEMA_REPRESENTATION)

Response message for openid.getJwks.

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

| Fields   |                                                                                                                     |
|----------|---------------------------------------------------------------------------------------------------------------------|
| `keys[]` | `object ( `[`Jwk`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/Jwks#Jwk)` )` The JWKs for this OP. |

## Jwk

A JSON web key set (JWK) See also <https://datatracker.ietf.org/doc/html/rfc7517> and <https://github.com/spiffe/spiffe/blob/main/standards/JWT-SVID.md#6-representation-in-the-spiffe-bundle> .

**JSON representation**

```
{
  "kty": string,
  "use": string,
  "kid": string,
  "n": string,
  "e": string,
  "alg": string
}
```

| Fields |                                                                      |
|--------|----------------------------------------------------------------------|
| `kty`  | `string` Key type. Currently "RSA".                                  |
| `use`  | `string` Public key use. Currently "sig".                            |
| `kid`  | `string` Key ID.                                                     |
| `n`    | `string` Modulus value for kty="RSA".                                |
| `e`    | `string` Exponent value for kty="RSA".                               |
| `alg`  | `string` Algorithm intended for use with the key. Currently "RS256". |
