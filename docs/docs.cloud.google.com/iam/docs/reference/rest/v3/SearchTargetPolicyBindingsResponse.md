---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/SearchTargetPolicyBindingsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/SearchTargetPolicyBindingsResponse
title: SearchTargetPolicyBindingsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3/SearchTargetPolicyBindingsResponse#SCHEMA_REPRESENTATION)

Response message for SearchTargetPolicyBindings method.

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

| Fields             |                                                                                                                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policyBindings[]` | `object ( `[`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings#PolicyBinding)` )` The policy bindings bound to the specified target. |
| `nextPageToken`    | `string` Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.                                             |
