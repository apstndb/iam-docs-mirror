---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/ListPolicyBindingsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/ListPolicyBindingsResponse
title: ListPolicyBindingsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/ListPolicyBindingsResponse#SCHEMA_REPRESENTATION)

Response message for ListPolicyBindings method.

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
| `policyBindings[]` | `object ( `[`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings#PolicyBinding)` )` The policy bindings from the specified parent. |
| `nextPageToken`    | `string` Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.                                             |
