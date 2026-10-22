---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/ListAttestationRulesResponse
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/ListAttestationRulesResponse
title: ListAttestationRulesResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/ListAttestationRulesResponse#SCHEMA_REPRESENTATION)

Response message for managedIdentities.listAttestationRules.

**JSON representation**

```
{
  "attestationRules": [
    {
      object (AttestationRule)
    }
  ],
  "nextPageToken": string
}
```

| Fields               |                                                                                                                                                  |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| `attestationRules[]` | `object ( `[`AttestationRule`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule)` )` A list of AttestationRules.         |
| `nextPageToken`      | `string` Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages. |
