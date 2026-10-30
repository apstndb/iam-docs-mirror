---
name: documents/docs.cloud.google.com/iam/docs/reference/sts/rest/v1/OpenIdProviderConfig
uri: https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/OpenIdProviderConfig
title: OpenIdProviderConfig
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/OpenIdProviderConfig#SCHEMA_REPRESENTATION)

Response message for well-known.getOpenid-configuration. Message fields are defined in <https://openid.net/specs/openid-connect-discovery-1_0.html#ProviderConfigurationResponse> .

**JSON representation**

```
{
  "issuer": string,
  "authorization_endpoint": string,
  "token_endpoint": string,
  "jwks_uri": string,
  "response_types_supported": [
    string
  ],
  "subject_types_supported": [
    string
  ],
  "id_token_signing_alg_values_supported": [
    string
  ]
}
```

| Fields                                    |                                                                                                                                                                                    |
|-------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `issuer`                                  | `string` URL using the https scheme with no query or fragment components that the OP asserts as its issuer identifier.                                                             |
| `authorization_endpoint`                  | `string` URL pointing to an authorization endpoint under this issuer. Note: Currently this endpoint returns a 404.                                                                 |
| `token_endpoint`                          | `string` URL pointing to a token endpoint under this issuer. Note: Currently this endpoint returns a 404.                                                                          |
| `jwks_uri`                                | `string` URL of the OP's JWK Set document, which MUST use the https scheme.                                                                                                        |
| `response_types_supported[]`              | `string` JSON array that contains a list of the OAuth 2.0 response_type values that this OP supports. Supported value: `idToken` .                                                 |
| `subject_types_supported[]`               | `string` JSON array that contains a list of the subject identifier types that this OP supports. Supported value: `public` .                                                        |
| `id_token_signing_alg_values_supported[]` | `string` JSON array that contains a list of the JWS signing algorithms (alg values) supported by the OP for the ID token to encode the claims in a JWT. Supported value: `RS256` . |
