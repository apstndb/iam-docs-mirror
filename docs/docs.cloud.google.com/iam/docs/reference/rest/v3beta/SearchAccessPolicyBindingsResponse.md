---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/SearchAccessPolicyBindingsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/SearchAccessPolicyBindingsResponse
title: SearchAccessPolicyBindingsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/SearchAccessPolicyBindingsResponse#SCHEMA_REPRESENTATION)

Response message for SearchAccessPolicyBindings rpc.

**JSON representation**

```
{
  "policyBindings": [
    {
      object (PolicyBinding)
    }
  ],
  "nextPageToken": string
}
```

| Fields             |                                                                                                                                                                                                        |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policyBindings[]` | `object ( `[`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings#PolicyBinding)` )` The policy bindings that reference the specified policy. |
| `nextPageToken`    | `string` Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.                                                       |
