---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore
title: TrustStore
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#SCHEMA_REPRESENTATION)
- [TrustAnchor](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#TrustAnchor)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#TrustAnchor.SCHEMA_REPRESENTATION)
- [IntermediateCA](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#IntermediateCA)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#IntermediateCA.SCHEMA_REPRESENTATION)

Trust store that contains trust anchors and optional intermediate CAs used in PKI to build a trust chain(trust hierarchy) and verify a client's identity.

**JSON representation**

```
{
  "trustAnchors": [
    {
      object (TrustAnchor)
    }
  ],
  "intermediateCas": [
    {
      object (IntermediateCA)
    }
  ]
}
```

| Fields              |                                                                                                                                                                                                                                                                                                                       |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `trustAnchors[]`    | `object ( `[`TrustAnchor`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#TrustAnchor)` )` Required. List of trust anchors to be used while performing validation against a given TrustStore. The incoming end entity's certificate must be in the trust chain of one of the trust anchors here. |
| `intermediateCas[]` | `object ( `[`IntermediateCA`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#IntermediateCA)` )` Optional. Set of intermediate CA certificates used for building the trust chain to the trust anchor. Important: Intermediate CAs are only supported for X.509 federation.                       |

## TrustAnchor

Represents a root of trust.

**JSON representation**

```
{

  // Union field kind can be only one of the following:
  "pemCertificate": string
  // End of list of possible types for union field kind.
}
```

| Fields                                                        |                                                                                                                                   |
|---------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Union field `kind` . `kind` can be only one of the following: |                                                                                                                                   |
| `pemCertificate`                                              | `string` PEM certificate of the PKI used for validation. Must only contain one ca certificate (either root or intermediate cert). |

## IntermediateCA

Intermediate CA certificates used for building the trust chain to trust anchor

**JSON representation**

```
{

  // Union field kind can be only one of the following:
  "pemCertificate": string
  // End of list of possible types for union field kind.
}
```

| Fields                                                        |                                                                                                |
|---------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| Union field `kind` . `kind` can be only one of the following: |                                                                                                |
| `pemCertificate`                                              | `string` PEM certificate of the PKI used for validation. Must only contain one ca certificate. |
